
[<img src="https://raw.githubusercontent.com/mailtoharshit/Weave/gh-pages/images/README.JPG" align="center" width="100%">](https://login.salesforce.com/)

# Weave 
====
A `.snippet` magician. Weave generates `.code-snippets` so that you type less and write more code.

## Features

* __Absurdly Complete__: We basically wrote template to generates powerful layout using material design
    and resolved day to day problem on writing lot of visualforce code, which for *years* we waited for Salesfroce to give.
    if it's in the spec, it's supported or will be added
* __Productive__: Speed up your salesforce development with quick commands, less pain on typing and maintaining code consistency
* __Modern__: Uses Material Design Layout and abrest of latest of frameworks.


## Before & After

![before and after 1](http://g.recordit.co/Kw2R4zfIIN.gif)

http://g.recordit.co/Kw2R4zfIIN.gif
http://g.recordit.co/89JzgDI5Gx.gif
http://mailtoharshit.github.io/Weave/images/vf_custom.gif
## Features

- Generates custom and standard visualforce boilerplate template
- Generates Material design ready templates
- Generates Jquery and Bootstrap ready visualforce templates

### Apex Code Snippets 
- Powerful Trigger and Trigger Handles class templates
- Support many more keywords to generates SOQL, Apex, Comment and more 
- Easy to install
- Stupidly easy to use, generates templates and keep pressing tab to see the magic

## Installation

### Option 1: PackageControl.io 

In

## Install

### Option 1: Manual

Copy the files to your Packages directory.

### Option 2: Package Control

In the command pallette (Cmd-Shift+P on Mac) type 'Install' then press enter to see a list of packages. Search for 'Weave' then press enter to install.

## Usage

With a blank .Page file open, type

    sf_html

and press `TAB`.

That generates:

    <apex:page standardStylesheets="false" showsidebar="false" showHeader="false" applyHtmlTag="false" docType="html-5.0">
     	<html xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">    	
            <head>
              <meta charset="utf-8" />
              <meta name="viewport" content="width=device-width, initial-scale=1" />
            </head>
            <body>
            </body>
      </html>
    </apex:page>

## License 

[MIT Licensed](https://github.com/mailtoharshit/Weave/blob/master/LICENSE).
