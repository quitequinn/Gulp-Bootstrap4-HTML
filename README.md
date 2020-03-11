
## Simple Setup to Automate HTML and SaSS changes using GULP4 and BrowserSync

If you are looking for a simple template or set up to automate your changes in your HTML or SaSS components feel free to clone this project. It uses GULP4 and BrowserSync to handle the automation. 

If you would like to fully understand how this works, check out my medium post 
[Setting up Gulp 4 for Bootstrap, SASS, and BrowserSync](https://medium.com/swlh/setting-up-gulp-4-0-2-for-bootstrap-sass-and-browsersync-7917f5f5d2c5?source=friends_link&sk=8d09a3d7b62fa11a35dd0b5156b6ab73)
to learn more about the source code and how to modify the Boostrap package and your SaSS file.

## To Run the Project
There is some software you need to install before you can use NPM.

Please install Homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

Then install NVM
```
brew install nvm
```
At the end of the installation process you will be asked to add some code to the .bash_profile in your root. If you don't have a .bash_profile you can just make one. It is a hidden file so you will have to click `COMMAND`+`SHIFT`+`.` to show all hidden files. Once you have found it copy the code asked at the end of the install.

You might be able to skip this step, but just incase install node 12
```
nvm install 12
```
And use node 12
```
nvm use 12
```
You are now ready to install this project.

## To Run the Project
After you download this project you may try to install all dependencies by opening this project in terminal and running 

```
npm install
```

Before you start the server, you need to install gulp 4 globally.

```
npm install gulp -g
```

Then run the command below.

```
gulp watch
```


Browsersync should automatically open a browser on port 3000.


# Customizing Bootstrap
You can customize bootstrap by changing variables above your import of bootstrap. 
All the variables you need are found on this page. https://github.com/twbs/bootstrap/blob/v4-dev/scss/_variables.scss
You can find your style.css file at `src/scss/styles.scss`.

