# Intro to git
* it is a version tracking tool
* to install git

#### Mac

```
$ brew install git
```
or

```
$ sudo port install git
```

#### Windows
* Go to git official website for installation
* Check the processor in your system.

```
https://git-scm.com
```
* separate setups will be present in windows appear like below as per the system.

##### Standalone installer
```
Git for Windows/x64 Setup.

Git for Windows/ARM64 Setup.
```
##### Portable ("thumbdrive edition")
```
Git for Windows/x64 Portable.

Git for Windows/ARM64 Portable.
```
#### Using winget tool
Install winget tool if you don't already have it, then type this command in command prompt or Powershell.
```
winget install --id Git.Git -e --source winget
```

#### Configuration for git in local system

* Go to terminal in vscode

```
git config --global user.mail "kannasrinivasulu8@gmail.com"

git config --global user.name "srinukanna"
```
* it prompts you enter the password of your system(mac/windows/linux).

### Creating a repository

* go to terminal

```
 mkdir "new repository name"
 cd "new repository location"
 git init
 git add .
 git commit -m 'gfg'
 git remote add origin ""
 git branch -M main
 git push origin main

```





