**Windows download link for Git:**

[**Git Website**]( http://git-scm.com/download/win)

[**Github:**]( http://windows.github.com)





# **Initial Customization**

## **Identity Setting**
After installing Git, users should immediately set the user name and email address, which will be used for every Git commit.
**Type the following into Terminal or Command Line:***

```
git config --global user.name "Jane Smith"

git config --global user.email "example@email.com"
To confirm that you have the correct settings, enter the following command:
git config --global user.name (should return Jane Smith)

git config --global user.email (should return example@email.com)
Check Settings

To check settings, use the git config --list command.
Example:
$ git config --list

user.name=Jane Smith

user.email=example@email.com

color.status=auto

color.branch=auto

color.interactive=auto

…
```


**Git Help Commands**


```
git help command

git command --help

man git-command
```
