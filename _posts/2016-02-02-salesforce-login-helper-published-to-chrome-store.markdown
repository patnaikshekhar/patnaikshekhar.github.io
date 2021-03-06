---
layout: post
title:  "Salesforce Login Helper published to Chrome App Store"
date:   2016-02-02 15:04:23
categories:
    - Salesforce
    - Force.com Logins
    - Salesforce Login Helper
tags:
    - Salesforce
    
---

Since Force.com logins became paid, I decided that it would be a good learning experience to create my own Salesforce keychain type of application.

The intent of this project is to be completly free and open source and hence I absolutely would love people to submit bugs, features and pull requests.

Source is available on [Github](https://github.com/patnaikshekhar/SalesforceLoginHelperChromeExtension).

It is now available on the chrome app store on the following [link](https://chrome.google.com/webstore/detail/salesforce-login-helper/lphjfeeaniomnoomcplfomgonemdmplf)

I have also uploaded a tutorial of the extension on [youtube](https://www.youtube.com/watch?v=0XVmU9s29zM&feature=youtu.be)

## Features

* Arranges Orgs by last accessed. If you click on an org it moves to the top of the list
* Search - If you have a lot of orgs the search box at the top will help you filter
* Can open tabs in Incognito Mode if that has been enabled.
* Syncs data across Chrome instances.
* Uses encryption so that the user name and password are not visible in the address bar
* Ability to extract org information in JSON format and import org information in the same format.

## About the technology 

This was my first experiment in using React and I must say I loved it. I've been using angular is most of my past projects and its been a fantastic experience. However react seemed a bit more intuitive with a lot less bells and whistles. Its more like going back to pure javascript. I've tried experimenting with Angular 2 however the alpha versions were way too unstable.

Some of the things that I want to incorporate in this in the future which I haven't got a chance to do so far is

* Writing test classes to cover the code
* Incorporating XML imports so that you can import your old Force.com logins file
* Using a framework like Redux to manage the Application state
* Create a Mac app based on the same code which shows a list of environments on the Menu Bar/ Task bar.
