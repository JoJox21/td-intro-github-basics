Version control enables the effective tracing and management of amendments executed on sources files/codes for softwares, webpages and other digital assets. This is being done by several systems such as Git, Monotone, CVS, Bazaar, Mercurial, SVN etc.

Git is a type of version control system that allows users to trace changes done on codes. It also allows for others users to work jointly in the creation of webpages and software. It comes at no cost to its users, and its interface is quite easy to understand.

Process of Committing a project to a repository on Github.
1.	Visit the website https://github.com
2.	Create an account by clicking sign up and if you have an account, click sign in and login with your username/email address and password.
3.	On logging in, to your left is a green button with caption NEW. Click on it for the creation of a new repository.
4.	This will take you to a new page where you’ll be asked to input a name for your repository (N.B: you cannot have two repositories with same name and spaces are not allowed in the name)
5.	Choose the type of repository you want. Choose PUBLIC If you want your source code to be seen by other, and PRIVATE if you want it to be seen by you alone or some selected people of choice.
6.	Add a README file so that you can provide details of what your source code is about.
7.	Proceed to click on “Create Repository” and a repository will be generated for you.
8.	After this is done, head on to Visual Studio Code and Select Terminal from the Menu bar (at the top). Choose New Terminal to produce the terminal page at the bottom (a CMD-like display).
9.	Before you are allowed to add your project to your repository, you have to declare your username and password to your github page (if it is your first time). To do that, input the commands below:
	git config --global user.email "youremail@yyyy.com" (press enter)
git config --global user.name "Your GitHub username" (press enter)
10.	type the following commands sequentially to commit the project to the respository
	git
	git init
	git add .
	git commit -m “title to your amendment”
11. 	After committing, the project can also be pushed to the repository be entering the following commands in sequence
	git branch -M main
git remote add origin “url of your profile.git”. For instance, git remote add origin https://github.com/beloved/first-git.git
	git push -u origin main

By following these steps, we have committed our code and pushed to the repository.
