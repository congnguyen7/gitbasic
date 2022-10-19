/git_day1
Getting Started

Nội dung:
    Tìm hiểu và thao tác với các câu lệnh cơ bản về git:
        git init
        git add
        git status
        git comit
        git diff
Tạo tài khoản github

/git_day2'
	git config --global user.name "congnguyen7"
	git config --global user.email "congnguyen@bkitsolution.com"
	cat ~/.gitconfig
	git config --list
	
	git clone https://github.com/congnguyen7/gitbasic.git
	cd gitbasic/
	echo "gitbasic " >> README.md
	cat README.md
	git add .
	git status
	git commit -m "first commit"
	git branch -M main
	git push origin main
<<<<<<< HEAD
	
	git config --global user.name "congnguyen7"
	git config --global user.email "congnguyen@bkitsolution.com"
	cat ~/.gitconfig
	git config --list
	
<<<<<<< HEAD
	
=======
	amend
>>>>>>> 506bf71 (update)
=======

/git_day3
	git commit –amend được sử dụng khi chúng ta muốn sửa đổi commit cuối cùng. 
	https://bom.so/58bVZ4 
>>>>>>> 3c0f59f (update README file)

	


