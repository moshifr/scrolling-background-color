
### Scrolling background color

Change the background color on scrolling

## Usage

1. Include jQuery & $.Color:

	```html
	<script src="http://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>
	<script src="http://code.jquery.com/color/jquery.color-2.1.0.js"></script>
	```

2. Include plugin's code:

	```html
	<script src="dist/jquery.scrolling-background-color.js"></script>
	```

3. Call the plugin:

	```javascript
    $(window).scrollingBackgroundColor(); // for the entire page background
		// or
    $('#element').scrollingBackgroundColor(); // for the background of #element
	```

## Demo

You will find a demo file on demo/index.html

## Structure

The basic structure of the project is given in the following way:

```
├── demo/
│   └── index.html
├── dist/
│   ├── jquery.scrolling-background-color.js
│   └── jquery.scrolling-background-color.min.js
├── .editorconfig
├── .gitignore
├── .jshintrc
├── .travis.yml
├── Gruntfile.js
└── package.json
```
