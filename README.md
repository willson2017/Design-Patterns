# simplegitrepo
simple git practice

#for an existing repository
git remote add origin https://github.com/willson2017/simplegitrepo.git

git push -u origin master

#list the remote url

git remote -v

#get the data from the remote by not merge the changes that are there with my work

git fetch origin


#get down the data from the remote along with any changes

git pull https://github.com/willson2017/simplegitrepo.git

#update to github (git status -s display the file which is changed(red color),  git add ./xxx.xxx , chage the file from red color to gree color, after that you can commit the file and the git push the file to remote server)red color show the file has changed
git add .
git commit -m "xxx"
git push





#git tag

git tag


