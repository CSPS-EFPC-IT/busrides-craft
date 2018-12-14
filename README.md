# Requirements

This project depends on:

Git
Nodejs and NPM
LAMP Stack
Server Requirements
# Installation

From the terminal/command line:

Run cd /path/to/webroot
Run git clone https://github.com/CSPS-EFPC-IT/elixir.git
Run cd elixir
Run composer install
Run npm install
Run npm run dev
(first time only) Import mysql database dump
# Configuration

There are many configuration options for your development environment.

Here is the configuration documentation.

# Development

This project is built on Craft CMS.

Craft 3 Documentation
Craft 3 Front-end Development
Craft 3 Plugin Development
This project also uses Laravel Mix to compile JavaScript and SCSS.

In a nutshell, you must run npm run watch to watch file changes while working with JavaScript and SCSS files. Mix will automatically rebuild the new assets without the need of running npm run dev every time.

Please read the documentation carefully to understand how it works.

# Guidelines

Never branch off master
Always develop locally on a feature branch based on develop
Always pull the latest changes before creating a new feature branch
Always squash commits when merging pull requests
Never commit third party libraries unless they can't be found using a package manager (composer, npm)
Always optimize assets (images) before committing
Prioritize readable code over comments (use comments only when absolutely necessary)
Use 2 spaces for indenting, not tabs
# Deployment

To be determined...