# DISMANTLE
###### An easy and lightweight css framework...


## How to use Dismantle?
Dismantle works with rows and columns to make it easy to create a layout for your website, using a standard 12 columns on a width of 960px.

To install it into your website just copy the content of the __assets/styles__ folder into your local style folder and link the file __framework.css__ in your html page like this:

```html
<link rel="stylesheet" href="styles/framework.css" type="text/css">
```

After you have done this, you can use Dismantle like this:

```html
<div class="row">
	<div class="col-3">
		<!-- Left sidebar goes here -->
	</div>
	<div class="col-9">
		<!-- Main content goes here -->
	</div>
</div>
```

Additionally Dismantle can pull content to the side by using the `pull` class together with the amount of colums you want the content to be pushed, like this:

```html
<div class="row">
	<div class="col-8 pull-4">
		<!-- content will be pulled 8 columns to the right -->
	</div>
</div>
```


## Responsive
Dismantle is designed to be responsive, wich means that on smaller screens it will automaticly resize and change its layout to be easier to read.


## Dependencies
Dismantle uses __Normalize.css__ for consistency, but its not needed for it to run.


## Version History
* v0.1 - Initial Release
* v0.1b - Bugfixes in demo file.


## Todo
- Add mobile columns
- Add different standard resolutions
- Add Typography styles


## License
Copyright (c) 2013 F. Rick Reich. Licensed under the terms of the MIT license.
http://frickreich.mit-license.org/
