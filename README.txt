## Environment Set Up
Installating ...
1. Git                         http://git-scm.com/downloads
2. GitHub                      https://github.com/
3. Python version 2.7.7        https://www.python.org/download
4. Virtual Environment         http://virtualenv.readthedocs.org/en/latest/virtualenv.html#installation
5. Pip                         http://pip.readthedocs.org/en/latest/installing.html
6. Django version 1.7.1        https://docs.djangoproject.com/en/dev/topics/install/
7. Unittest2  version 0.6.0    https://pypi.python.org/pypi/unittest2

Editor: Sublime Text

After installing...
Create a folder Ufundi on your desktop using command
> cd /path/Desktop
> mkdir Ufundi

Create virtual enviroment
> virtual env Ufundi_env

Activate environment
> Ufundi_env\Scripts\activate

Now you are in virtual enviroment
> (Ufundi_env)/path/Desktop/Ufundi/

GIT
On command prompt or Git Bash
You can Clone this repo using
> git clone https://github.com/lillian7/Ufundi-Crafts-Shop/Ufundi_src-.git

When you have made changes.. to the app remember to Add your changes, commit them and push to the repo.
> git add file
> git commit -m "first commit"
> git remote add origin https://github.com/lillian7/Ufundi-Crafts-Shop-.git
> git push -u origin master

Remember to pull changes made by the other teammates to keep updated
> git pull [options] [<repository> [<refspec>...]]

Heroku
On command prompt 
> cd into Ufundi
> heroku create ufundi
> git push heroku master

