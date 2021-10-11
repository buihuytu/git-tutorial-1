# Git Tutorial

## I.	Các khái niệm 
```
1.	Repositories - Repo: kho chứa source code
Readme
gitignore
ex name: codelearn-algorithms 
•	Tên Repo nên để dấu gạch ngang (-) thay vì gạch dưới (_), dễ nhận biết nội dung bên trong repo, dễ hiểu, đúng ý nghĩa nội dung dự của dự án 
•	Username nên đặt để dễ nhận biết, đơn giản, dễ nhớ 
2.	Branches: nhánh => main (kiểu default). Một repo có thể có nhiều nhánh
Ex: Repo1:
-	main/master (nhánh default, khi tạo 1 repo sẽ luôn có)(ver1)–File A, B, C
-	develop (ver2)
-	stadevelo (ver3)
-	release-20211005 (ver4)
Chức năng: Các nhánh con có thể chứa file của các nhánh cha, mỗi 1 nhánh có thể chứa các code khác nhau 
3.	Commits: khi tạo 1 repo và chọn file readme thì nó sẽ tự tạo commit.
Danh sách chỉnh sửa, up file trong repo
Commit luôn đi cùng với Mã h – hash commit: checking - để kiểm tra xem ai thêm/ tạo/ sửa file hay commit   
4.	Pull Request (PR): chứa các yêu cầu của người dùng 
5.	Merge: gộp các nhánh phụ vào 1 nhánh chính 
6.	Fork 
```
## II.	Các lệnh bash – command shell/bash: 
```
cd: di chuyển vào thư mục 
ls: hiển thị danh sách các file và thư mục 
git clone: đưa code từ repo github về máy 
git status: hiển thị trạng thái
git branch: hiển thị danh sách các nhánh
git add. : thêm file vào trạng thái staged trước khi commit
git commit –m “Create file danh_sach_lop.txt”
git log –oneline -10: hiển thị danh sách 10 commit gần nhất 
git push origin main: đẩy code lên repo github 
git checkout –b <branch>: tạo nhánh mới và di chuyển sang nhánh đó 
git switch –c  <branch> : tạo nhánh mới và di chuyển sang nhánh đó
git checkout <branch>: chuyển sang nhánh branch
git switch <branch>: chuyển sang nhánh branch
git pull origin main: kéo code mới nhất về 
pull: kéo về 
push: đẩy lên 
file có đuôi .pub: khóa công khai
```


