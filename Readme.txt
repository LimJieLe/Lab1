# ET0735 – Lab 1 (Introduction to Git and GitHub)

git config --global user.name {your name}
Example: git config --global user.name "LimJieLe" 

git config --global user.email {your email}
Example: git config --global user.email JIELE.21@ichat.sp.edu.sg

git config --list 

cd "D:\Local_Git_Repository" 
cd..

mkdir {name of new directory for new Git repository}

git init

git status

git add HelloWorld.py/git add *

git commit -m "Initial version to display text message on console"
git commit --amend

git branch //view all branches
git branch "bug-fix1" //create new branch
git checkout "bug-fix1" //switch to the new branch
git checkout "master" 
git merge "bug-fix1" 
 
git remote add origin https://GitHub.com/kweetecktanichat/Lab1.git
git remote –v //check if the currently local Git repository has the remote repository server correctly configured
git remote set-url origin {URL} //Update the remote origin to the URL of your ne Github repository
git push --set-upstream origin master
git push –u origin
git tag –a v1.0 –m "Initial release v1.0" 
git push origin v1.0

git submodule add <Git submodule repository URL> 
git clone <URL of repository to clone>
git log

How do I "git clone" a repo, including its submodules?
git clone --recurse-submodules -j8 git://github.com/foo/bar.git
git clone --recursive -j8 git://github.com/foo/bar.git
cd bar