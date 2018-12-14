# Requirements

This project depends on:

- Git
- Nodejs and NPM
- LAMP Stack
- Server Requirements

# Installation

From the terminal/command line:

- Run `cd /path/to/webroot`
- Run `git clone https://github.com/CSPS-EFPC-IT/busrides-craftcms.git busrides`
- Run `cd busrides`
- Run `composer install`
- Run `npm install`
- Run `npm run dev`
- Run `./craft setup/security-key`
- (first time only) Import mysql database dump

# Configuration

To be continued...

# Development

This project is built on Craft CMS.

- Craft 3 Documentation
- Craft 3 Front-end Development
- Craft 3 Plugin Development
- This project also uses Laravel Mix to compile JavaScript and SCSS.

In a nutshell, you must run `npm run watch` to watch file changes while working with JavaScript and SCSS files. Mix will automatically rebuild the new assets without the need of running npm run dev every time.

Please read the documentation carefully to understand how it works.

# Deployment

To be continued...