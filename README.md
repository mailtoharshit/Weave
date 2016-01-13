# Weave
Snippets to generate the Salesforce Boilerplate Code

[<img src="http://i.imgur.com/sCOjb0V.jpg?1" align="center" width="100%">](https://login.salesforce.com/)

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
