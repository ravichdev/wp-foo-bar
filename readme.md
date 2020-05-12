<!-- DO NOT EDIT THIS FILE; it is auto-generated from readme.txt -->
# Foo Bar Plugin for WordPress

![Banner](wp-assets/banner-1544x500.png)
WordPress plugin template for extending Gutenberg at XWP.

**Contributors:** [xwp](https://profiles.wordpress.org/xwp)  
**Requires at least:** 5.0  
**Tested up to:** 5.3.2  
**Stable tag:** 0.0.1  
**License:** [GPLv2 or later](http://www.gnu.org/licenses/gpl-2.0.html)  

[![version](https://badge.fury.io/gh/xwp%2Fwp-foo-bar.svg)](https://badge.fury.io/gh/xwp%2Fwp-foo-bar) [![Build Status](https://travis-ci.org/xwp/wp-foo-bar.svg?branch=develop)](https://travis-ci.org/xwp/wp-foo-bar) [![Coverage Status](https://coveralls.io/repos/xwp/wp-foo-bar/badge.svg?branch=develop)](https://coveralls.io/github/xwp/wp-foo-bar) [![Built with Grunt](https://gruntjs.com/cdn/builtwith.svg)](http://gruntjs.com) 

## Description ##

**Scaffolding**

Use the [`init-plugin.sh`](init-plugin.sh) bash script to scaffold a new plugin. The script will enter an interactive shell on your host machine and copy this plugin while making necessary string replacements:

```bash
./init-plugin.sh
```

The `init-plugin.sh` script will be removed from the generated plugin. You should also update your `readme.txt` and add/change any of the config files your project may need, read more about your options in the [`xwp/wp-dev-lib/readme.md`](https://github.com/xwp/wp-dev-lib) file.

**Coveralls Pro**

To use Coveralls Pro with your private repository you will need to change the `service_name` inside `.coveralls.yml` to `travis-pro`, and add the `COVERALLS_REPO_TOKEN` to the settings in Travis CI. If you don't want to use Coveralls then you will need to delete the `.coveralls.yml` and remove `npm run test:js:coveralls` step from the script section in the `.travis.yml` file.

**Adding Classes**

When adding a new class you should instantiate it in `Plugin::init` and inject `Plugin` as a dependency. There is a `Sample` class inside the `php` directory that demonstrates this behavior and how doc hooks work.

## Installation ##

1. Upload the folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.

## Frequently Asked Questions ##

### A question that someone might have ###
An answer to that question.


## Getting Started ##

If you are a developer, we encourage you to [follow along](https://github.com/xwp/wp-foo-bar) or [contribute](https://github.com/xwp/wp-foo-bar/contributing.md) to the development of this plugin on GitHub.

## Screenshots ##

### Look at this demo photo!

![Look at this demo photo!](wp-assets/screenshot-1.png)

## Changelog ##

For the plugin’s changelog, please see [the Releases page on GitHub](https://github.com/xwp/wp-foo-bar/releases).

