# DISMANTLE
###### An easy and lightweight mobile-first css framework...


## How to use Dismantle
Dismantle works with rows and columns to make it easy to create a layout for your website, using a standard 12 columns on a width of 960px.

To install it into your website just copy the content of the __assets/styles__ folder into your local style folder and link the file __framework.css__ in the head of your HTML file like this:

```html
<link rel="stylesheet" href="styles/framework.css" type="text/css">
```

### Rows and Columns

After you have done this, you can use Dismantle like this:

```html
<div class="container">
	<div class="row">
		<div class="col-3">
			<!-- Left sidebar goes here -->
		</div>
		<div class="col-9">
			<!-- Main content goes here -->
		</div>
	</div>
</div>
```

### Nesting

You can easily stack grads into each other too by nesting the row/column layout.

```html
<div class="container">
	<div class="row">
		<div class="col-3">
			<!-- A sidebar -->
		</div>
		<div class="col-9">
			<div class="row">
				<div class="col-8">
					<!-- main content inside of another column -->
				</div>
				<div class="col-4">
					<!-- more content area inside of a different column -->
				</div>
			</div>
		</div>
	</div>
</div>
```

### Pulling Columns

Dismantle can pull content to the side by using the `pull` class together with the amount of colums you want the content to be pushed, like this:

```html
<div class="container">
	<div class="row">
		<div class="col-8 pull-4">
			<!-- content will be pulled 8 columns to the right -->
		</div>
	</div>
</div>
```

In addition you can pull any content on the far right by using the `pull-right` class.

### Mobile First

Since Dismantle is mobile first you can specify columns differenly from the desktop layout. 
Desktop columns will always reset to 100% unless you use the `mobile` class on them.

```html
<div class="container">
	<div class="row">
		<div class="col-10 mobile-8">
			<!-- this is 10 columns on desktop and 8 columns on mobile -->
		</div>
		<div class="col-2 mobile-4">
			<!-- this is 2 columns on desktop and 4 on mobile -->
		</div>
	</div>
</div>
```

## Responsive
Dismantle is designed to be responsive, wich means that on smaller screens it will automaticly resize and change its layout to be easier to read.

### Different page width templates.

For desktop layout its possible to use different sizes of grid layouts by using an alternate `container` class, possible are:

* `.container` = 960 pixels wide.
* `.container-320px` = 320 pixels wide.
* `.container-720px` = 720 pixels wide.
* `.container-768px` = 768 pixels wide.
* `.container-1218px` = 1218 pixels wide.
* `.container-1382px` = 1382 pixels wide.
* `.container-fluid` = 100% page width.

find out more at the dismantle.gs wiki: <https://github.com/FRickReich/Dismantle/wiki/Dismantle-dismantled>

## Dependencies
Dismantle uses __Normalize.css__ for consistency, but its not needed for it to run.


## Version History
* v0.1 - Initial Release.
* v0.1b - Bugfixes in demo file.
* v0.2 - Added mobile grid.
* v0.3 - Added multiple resolution grid.
* v0.4 - Added more demos and minified version.


## Todo
- Typography styles.


## License
Copyright (c) 2013 F. Rick Reich. Licensed under the terms of the MIT license.
http://frickreich.mit-license.org/
