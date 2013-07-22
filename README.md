jQuery-Nice-File-Input
======================

The jQuery Nice File Input Plugin provides batter looking file input HTML element, while making all kinds of customizations to fit your application really easy.
Have a look at <a href="http://jaydevgajera.com/nice-file-input/" target="_blank" >demo page</a>. 

##Features

* Lightweight (~0.95kb)
* Optional width for file input element
* Optional width for 'Browser' button
* Automatic adjust size attribute in Firefox version < 22     

##Compatibility

jQuery Nice File Input has been tested with jQuery 1.9+ on all major browsers:

* Firefox 2+ (Win, Mac, Linux)
* IE8+ (Win)
* Chrome 6+ (Win, Mac, Linux)
* Safari 3.2+ (Win, Mac)
* Opera 8+ (Win, Mac, Linux)


##Usage

Downloading the code:

https://raw.github.com/jaydevonline/jQuery-Nice-File-Input/master/dist/jquery.nice-file-input.min.js
or
https://raw.github.com/jaydevonline/jQuery-Nice-File-Input/master/dist/jquery.nice-file-input.js

https://raw.github.com/jaydevonline/jQuery-Nice-File-Input/master/demo/css/jquery.nicefileinput.css

The only thing that you need to do is include the javascript and CSS files of the plugin in your HTML document and it is all set to use.

##The syntax

The jQuery Nice File Input Plugin syntax is pretty simple. 
First, you input your  selector, followed by the .niceFileInput and then as a parameters you have to put the width options and button text that you want the plugin to apply on the file input field.

###Example

 ```HTML
<input type="file" class="nicefile" />
 ```


 ```javascript
$('document').ready(function(){		
	$(".nicefile").niceFileInput();				
});	
 ```
In this example the jQuery Nice File Input Plugin  will be applied in all the input fields that have the '.nicefile' class with default options.

You can choose the setting options as you wish also like this.

 ```javascript
$('document').ready(function(){					
	$(".nicefile").niceFileInput({
		'width'   : '500', //width of button - minimum 150
		'height'  : '30',  //height of text
		'btnText' : 'Browse', //text of the button     
		'btnWidth': '100' ,  // width of button
	    'margin'  : '20',	// gap between textbox and button - minimum 14 		  
	});				
});
 ```

> The jQuery Nice File Input Plugin takes '150' as minimum width in px for 'width' option.

> For option 'margin' it should be minimum  14, here this digit is not showing px value. It is set by some calculation.

> style can be changed by editing the stylesheet jquery.nicefileinput.css


Any problems, please, let me know. 

Twitter  : <a href="https://twitter.com/jaydevonline" target="_blank" >@jaydevonline</a>

LinkedIn : <a href="in.linkedin.com/in/jaydevgajera/" target="_blank"> in.linkedin.com/in/jaydevgajera/ </a>









 









