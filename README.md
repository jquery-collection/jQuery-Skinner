<h1>jQuery-Skinner</h2>
==============

A jQuery plugin for skin a html combobox (select)
<br>
If you find any bug, report it on twitter [@anbi](http://www.twitter.com/anbi).

<h2>Usage</h2>
<p>Include Javascript and Stylesheet</p>
```html
<script src="js/jquery-skinner.js" type="text/javascript"></script>
<link href="css/jquery-skinner.css" rel="stylesheet" />
```
<p>Insert html select tag with classname:</p>
```html
<select class="myNewSelect">					
	<option>Banana</option>
	<option>Cucumber</option>
	<option selected="selected">Strawberry</option>
	<option>Hedge apple</option>
	<option>Boysenberry</option>
	<option>Apple</option>
	<option>Pomegranate tree</option>
</select>
```
<p>Insert Javascript</p>
```javascript
$(function(){			

	$('.myNewSelect').skinner({'width':'200px', 'maxitem':'4'});
		
});
```

<h3>List of params</h3>
```javascript
	$('.myNewSelect').skinner({
		'type':'left',		// Floating of element i.e. 'left' or 'right'
		'width':'150px',	// Specify a fixed width in pixel i.e. '150px
		'maxitem':false,	// Maximum number of item to show i.e. '4'
		'textwrap':true		// Force text wrap at width of select i.e true or false
	});
```	
