Notice:

No longer maintained. (Never been maintained before.)

Licensed under GPL. (You know it...)

Ditsributed  without any waranty. 

potrace
=======

A javascript port of [Potrace](http://potrace.sourceforge.net)

[online demo](http://kilobtye.github.io/potrace/)

**NEW ADDITION**
================

Potrace can be used from serverside, by just using command, where only **potrace_serverside.js** file is required.

Usage of Potrace serverside:

 

 1. You have to install "[node](https://nodejs.org/en/download/)" to run js file from command.
 2. Install "[canvas](https://www.npmjs.com/package/canvas)". There can be two approach, One is install it by **npm** another one is install it by **yarn**. You can use any of them. I had some issue with npm, that's why I applied yarn approach.  
 
	Installation from **npm**:
	===================
	 $ `npm install canvas`
	
	Installation from **yarn**:
	===================

    $ `curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -`
    
    $ `echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list`
    
    $ `sudo apt-get update`
    
    $ `sudo apt-get install yarn`
    
    $ `yarn install`
    
    $ `yarn add canvas`

 3. Now you are done, and you can use `potrace_serverside.js`
 4. Now run command (this will return svg data you have to use that output to save it as svg file by your programming language that you are using):
 
	$ `node [potrace_serverside.js directory] [image directory]` 
	
