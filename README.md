# README #
This plugin pretty prints php code for programatically creating fields and fields instances,  for use with a site deployment module in function implementing hook_update_N.

## Requirements ##
The module requires that you have drush installed and are executing the function within a drupal installation directory.
Installation has only been tested using [pathogen](https://github.com/tpope/vim-pathogen).

## Installation ##
To install this plugin with pathogen, run the following in a terminal:


```
#!shell

cd ~/.vim/bundle
git clone https://bitbucket.org/lbuzzo/vim-drupal-field-export.git
```

## Usage ##
In normal mode, place the cursor over the machine name of a Drupal field and execute the command `:call DrupalExportField()`, this will replace the machine name with valid php export code.