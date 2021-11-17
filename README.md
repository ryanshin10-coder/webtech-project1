# webtech-project1
Project: Franken-showcase of web tech
Due Tuesday November 30th 11:55pm

Create an SPA that features some interactive data with d3. Try to use this SPA as an exploration of code/tech examples to refer to later. This means writing comments for your future self that will help you understand what you did. Also, you may be able to add this to your portfolio.

Your SPA project must have:
- A project git : github or heroku
- A READ_ME.txt file with (in this order)
. your name and email
. Project Check-list
. a git log --all
- A server.js (nodejs) file that serves an index.html written with
. that runs by “node server.js”
. external link: https://localhost:3000 views your SPA (index.html…)
- A d3 data display component using
. updatable data that is originally from a JSON file
. a join with enter, exit and transitions
- A non trivial css file with
. Hover/focus/active codes
. Borders with rounded corners
. Gradient backgrounds
- A least one unicode Emojis
- A non-d3 svg that contains at least one:
. circle, path, rect, text element
- HTML elements must include a least one
. Button, H1, list (either ul or ol), link, image
- Javascript arrow functions
. use at least one
- In comments, show
. links to original sources / where you found the code
for my files, you can just refer to them by name (eg. data4njq.html)
. indicate how much different your code
Fulfilling the Project Check-list will be 80% of your grade with the last 20% based on the quality, value and creativity of work. Each entry in the check-list must indicate line-numbers that are responsible for fulfilling the entry and where applicable must be at some point visible in the SPA. An example of the Check-list will be provided before the project is due.
# git
git: local repository
github: remote repository

git: commit (local save)
github: push (remote upload)

master, branch

- Basic Usage -
1. repository creation (git: git init, github: create new repository)
2. git add Filename or *.extention / git add . (all files)
3. git commit -m "message"
4. git status : check
5. git remote add origin https://github.com/Username/RepositoryName
6. git push origin(remote) master or git push origin bran01
7. git pull (git pull origin(remote) master)
8. git clone [url] : download to local
9. git checkout master
10. git merge bran01
11. git log
12. git grep
13. git remote : 원격 저장소 목록 표시, -v: 세부 목록, add(#5), rm
14. git reset -soft HEAD ^ 

- Basic Concept -
![git](https://user-images.githubusercontent.com/68491757/142260638-1fcdee47-7d2c-4905-8ab9-973462029afc.PNG)




- Branch -

git branch : branch check
git checout -b bran01 (git branch bran01 & git checkout bran01)
git branch -d bran01 : delete branch
