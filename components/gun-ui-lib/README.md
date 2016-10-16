gun-ui-lib
==========
> main component of the gun-ui library.
> A collection of widgets created to work brilliantly with GUN, or without.

## NOTE: 
There is no need ( or purpose ) to load this element by yourself. All widget components of the gun-ui library have this element as a dependency, if you  `bower install` any of the widgets this will be included for you. ( Except for 'gun-ui-lcd' which doesn't need it ).

## gun-ui-lib(rary)
curently the library consists of;
<pre>
gun-ui-lib       : https://github.com/Stefdv/gun-ui-lib     ( you`re already here )     CORE
gun-ui-gauge     : https://github.com/Stefdv/gun-ui-gauge                               DATA-VIZ   
gun-ui-bargauge  : https://github.com/Stefdv/gun-ui-bargauge                            DATA-VIZ   
gun-ui-lcd       : https://github.com/Stefdv/gun-ui-lcd                                 DATA-VIZ   
gun-ui-slider    : https://github.com/Stefdv/gun-ui-slide                               INPUT / DATA-VIZ
</pre>


Disclamer:
_All canvas elements in the gun-ui library are created by Gerrit Grunwald (@hansolo)_**

## What is it ?
by itself it is not very usefull. But all gun-ui elements require this element. It is basically loading the stripped-down version of Gerrit Grunwald's steelseries library for javascript. (http://harmoniccode.blogspot.nl/2011/01/canvas-steel.html)

## Stripped-down?
Yes, the original file holds all widgets in a single file. I needed every widget as a single component and didn't want to pack the original file with each element due to filesize.


syncing

gun-ui-lcd , gun-ui-gauge and gun-ui-bargauge 
![alt text](https://cloud.githubusercontent.com/assets/890650/19337265/e26abdcc-9113-11e6-9fea-e5d8a66bff31.gif)
_All canvas elements in the gun-ui-lib are created by Gerrit Grunwald (@hansolo)_**
