Jaggeryjs SublimeText Package
==============================

This is a Sublime Text package to help with [Jaggeryjs](http://jaggeryjs.org/). 

Overview
-----------------------
Jaggery is a framework to write webapps and HTTP-focused web services for all aspects of the application: front-end, communication, Server-side logic and persistence in pure Javascript. One of the intents of this framework is to reduce the gap between writing web apps and web services. Jaggery is open-source and released under Apache 2.0.

Package Includes
--------------------------
- Syntax highlighting
- Snippets
- Code Completion
- jaggery.conf generation

## Installation ##

### With Package Control ###

If you have the [Package Control][package_control] package installed, you can install jaggeryjs package from inside Sublime Text itself. Open the Command Palette(<code>ctrl+shift+p</code> or <code>⌘+shift+p</code>) and select "Package Control: Install Package", then search for **Jaggeryjs** .

### Without Package Control ###

If you haven't got Package Control installed you will need to make a clone of this repository into your packages folder, like so:

    git clone https://github.com/dakshika/jaggeryjs-sublime-text.git jaggeryjs

#### For Linux:

	$ cd ~/.config/sublime-text-2/Packages/
	$ git clone https://github.com/dakshika/jaggeryjs-sublime-text.git jaggeryjs

#### For OSX

	$ cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
	$ git clone https://github.com/dakshika/jaggeryjs-sublime-text.git jaggeryjs

#### For Windows

	$ cd %APPDATA%/Sublime Text 2/Packages/
	$ git clone https://github.com/dakshika/jaggeryjs-sublime-text.git jaggeryjs
	

## Snippets Short Codes ##
----------------------------------------

- <code>jagHTML5</code> : HTML5 page template for Jaggery.
- <code>jag</code> : escaping characters for Jaggery. 
- <code>jagprint</code> :  escaping characters for print out server-side data.
- <code>jagconf</code> : configuration file specifies the application specific configurations.
- <code>jagXMLHTTP</code> : functionality of server side XML HTTP communication.
- <code>jagDB</code> : Database Object used to connect to a relational database.
- <code>jagSender</code> : Add-on object allows users to send out email from their apps.
- <code>jagOauth</code> : OAuthProvider api act as an oauth client for accessing resources protected by OAuth.
- <code>jagOauthRequest</code> : OAuthRequest snippets. 
- <code>jagProcess</code> : Add-on allows to access to externally defined properties and environment variables.
- <code>jagi18n</code> : Add-on provides the ability to internationalize text in webapps.

[sublime]: http://www.sublimetext.com/
[package_control]: http://wbond.net/sublime_packages/package_control

## Screenshot ##
============================================

![Alt text](http://3.bp.blogspot.com/-4-jMKpWEc0c/U3qSkehthsI/AAAAAAAAAvs/pF-VLCAdXqk/s1600/screenshot001.gif "Jaggeryjs Sublime Text")

If you find error or whatever just fork it and send me a pull request.
