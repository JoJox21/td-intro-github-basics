What is Version Control?
Version control enables the effective tracing and management of amendments executed on sources files/codes for softwares, webpages and other digital assets. This is being done by several systems such as Git, Monotone, CVS, Bazaar, Mercurial, SVN etc.

What is Git?
Git is a type of version control system that allows users to trace changes done on codes. It also allows for others users to work jointly in the creation of webpages and software. It comes at no cost to its users, and its interface is quite easy to understand.

Process of Committing a project to a repository on Github.
1.	Visit the website https://github.com
2.	Create an account by clicking sign up but if you have an account, click sign in and login with your username/email address and password.
3.	On logging in, to your left is a green button with caption NEW. Click on it for the creation of a new repository.
4.	This will take you to a new page where you’ll be asked to input a name for your repository (N.B: you cannot have two repositories with same name and spaces are not allowed in the name)
5.	Choose the type of repository you want. Choose PUBLIC If you want your source code to be seen by others, and PRIVATE if you want it to be seen by you alone only you or some selected people of choice.
6.	Add a README file so that you can provide details of what your source code is about.
7.	Proceed to click on “Create Repository” and a repository will be generated for you.
8.	After this is done, head on to Visual Studio Code and Select Terminal from the Menu bar (at the top). Choose New Terminal to initiate the terminal page at the bottom (a CMD-like display).
9.	Before you are allowed to add your project to your repository, you have to declare your username and password to your github page (if it is your first time). To do that, input the commands below:
	<p>git config --global user.email "youremail@yyyy.com" (press enter)</p>
    <p>git config --global user.name "Your GitHub username" (press enter)</p>
10.	type the following commands sequentially to COMMIT THE PROJECT TO THE RESPOSITORY GIT
	<p>git init</p>
	<p>git add .</p>
	<p>git commit -m “title to your amendment”</p>
11. 
    <p>After committing, the project can also be pushed to the repository by entering the following commands in sequence</p>
	<p>git branch -M main</p>
    <p>git remote add origin “url of your profile.git”. (For instance, git remote add origin https://github.com/beloved/first-git.git)</p>
	<p>git push -u origin main</p>

By following these steps, you’d have successfully committed your code and pushed to the repository.

Thank you.
