# T4 Templates #

Repository of my custom T4 templates.

## What is T4? ##

Learn more here: http://msdn.microsoft.com/en-us/library/vstudio/bb126445.aspx

## Template: resources.tt ##

Generates seperate JavaScript files from your .resx files.

The way you use it, is to place the .tt file inside your Scripts folder and 
name it what you want your final output to be, eg. "resources.tt" will create
"resources.js", "resources.nb-NO.js", etc.

It will read your .resx files inside the standard Properties folder.

## Template: manager.ttinclude ##

This is written my Damien Guard and is linked in the resources.tt template.

http://damieng.com/blog/2009/11/06/multiple-outputs-from-t4-made-easy-revisited