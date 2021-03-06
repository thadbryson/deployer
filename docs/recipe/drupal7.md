<!-- DO NOT EDIT THIS FILE! -->
<!-- Instead edit recipe/drupal7.php -->
<!-- Then run bin/docgen -->

# drupal7

[Source](/recipe/drupal7.php)



* Require
  * [`recipe/common.php`](/docs/recipe/common.md)
* Config
  * [`drupal_site`](#drupal_site)
  * [`shared_dirs`](#shared_dirs)
  * [`shared_files`](#shared_files)
  * [`writable_dirs`](#writable_dirs)
* Tasks
  * [`deploy`](#deploy)
  * [`drupal:settings`](#drupalsettings)
  * [`drupal:upload_files`](#drupalupload_files)

## Config
### drupal_site
[Source](https://github.com/deployphp/deployer/search?q=%22drupal_site%22+in%3Afile+language%3Aphp+path%3Arecipe+filename%3Adrupal7.php)

Set Drupal 7 site. Change if you use different site

### shared_dirs
[Source](https://github.com/deployphp/deployer/search?q=%22shared_dirs%22+in%3Afile+language%3Aphp+path%3Arecipe+filename%3Adrupal7.php)

* Overrides [`shared_dirs`](/docs/recipe/common.md#shared_dirs) from `recipe/common.php`

Drupal 7 shared dirs

### shared_files
[Source](https://github.com/deployphp/deployer/search?q=%22shared_files%22+in%3Afile+language%3Aphp+path%3Arecipe+filename%3Adrupal7.php)

* Overrides [`shared_files`](/docs/recipe/common.md#shared_files) from `recipe/common.php`

Drupal 7 shared files

### writable_dirs
[Source](https://github.com/deployphp/deployer/search?q=%22writable_dirs%22+in%3Afile+language%3Aphp+path%3Arecipe+filename%3Adrupal7.php)

* Overrides [`writable_dirs`](/docs/recipe/deploy/writable.md#writable_dirs) from `recipe/deploy/writable.php`

Drupal 7 writable dirs


## Tasks
### deploy
[Source](https://github.com/deployphp/deployer/search?q=%22deploy%22+in%3Afile+language%3Aphp+path%3Arecipe+filename%3Adrupal7.php)



This task is group task which contains next tasks:
* [`deploy:prepare`](/docs/recipe/common.md#deployprepare)
* [`deploy:publish`](/docs/recipe/common.md#deploypublish)


### drupal:settings
[Source](https://github.com/deployphp/deployer/search?q=%22drupal%3Asettings%22+in%3Afile+language%3Aphp+path%3Arecipe+filename%3Adrupal7.php)

Create and upload Drupal 7 settings.php using values from secrets

### drupal:upload_files
[Source](https://github.com/deployphp/deployer/search?q=%22drupal%3Aupload_files%22+in%3Afile+language%3Aphp+path%3Arecipe+filename%3Adrupal7.php)

Upload Drupal 7 files folder

