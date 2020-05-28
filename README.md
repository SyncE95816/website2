#Sample Website
This is a walk through on my own setting up a simple Website following the learnenough to be Dangerous course on GIT.

not all git status, etc. are shown below:

[repos]$ mkdir website2
[repos]$ cd website2
[website2]$ git init
website2 (master)]$ atom index.html
[website2 (master)]$ mkdir images
[website2 (master)]$ mv IMG_7459.jpeg images/warthog.jpeg
[website2 (master)]$ git status
[website2 (master)]$ git add -A
[website2 (master)]$ git commit -am "Add new Index"

log into github and create a new repository called website2
copy the links they present back into the command line:

[website2 (master)]$ git remote add origin https://github.com/SyncE95816/website2.git
[website2 (master)]$ git push -u origin master

[website2 (master)]$ atom README.md
[website2 (master)]$ atom about.html

save images in image directory

*
git add -A  (to add new image, README and about!!)
*
