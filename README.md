# grunt-wp-plugin

> Create a WordPress plugin with [grunt-init][] based on the [WordPress Plugin Boilerplate](https://github.com/tommcfarlin/WordPress-Plugin-Boilerplate)

[grunt-init]: http://gruntjs.com/project-scaffolding

# Submodule

See Eclipse plugin for handling submodules

    http://wiki.eclipse.org/EGit/User_Guide#Working_with_Submodules
    git submodule add https://github.com/tommcfarlin/WordPress-Plugin-Boilerplate.git root
    
The git command to pull the repo

    git clone --recursive https://github.com/emeraldjava/grunt-wp-boilerplate.git C:\Users\oconnellp\\.grunt-init\wp-boilerplate-emeraldjava

## Installation
If you haven't already done so, install [grunt-init][]:

```
npm install -g grunt-init
```

Once grunt-init is installed, place this template in your `~/.grunt-init/` directory. It's recommended that you use git to clone this template into that directory, as follows:

### Linux/Mac Users

```
git clone git@github.com:fooplugins/grunt-wp-boilerplate.git ~/.grunt-init/wp-boilerplate
```

### Windows Users

```
git clone git@github.com:fooplugins/grunt-wp-boilerplate.git %USERPROFILE%/.grunt-init/wp-boilerplate
```

## Usage

1. At the command-line, create a new directory in wp-content/plugins
2. cd into an empty directory
3. run the following command and follow the prompts

```
grunt-init wp-boilerplate
```
_Note that this template will generate files in the current directory, so be sure to change to a new directory first if you don't want to overwrite existing files._

## Screenshots

## Credit

Most of this is copied from [grunt-wp-plugin](https://github.com/10up/grunt-wp-plugin) by 10up, so thanks to them!