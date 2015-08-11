# Piecon

Pie charts in your favicon! A tiny javascript library for dynamically generating progress pie charts in your favicons.

Now with retina support!

<p align="center"><img src="https://github.com/lipka/piecon/blob/master/example/screenshot.png?raw=true"></p>

See the [live demo here](http://lipka.github.com/piecon/).

## Documentation

### Basic usage

```javascript
Piecon.setProgress(12);
Piecon.setProgress(25);
...
Piecon.reset();
```

### Options

```javascript
Piecon.setOptions({
  color: '#ff0084', // Pie chart color
  background: '#bbb', // Empty pie chart color
  shadow: '#fff', // Outer ring color
  fallback: false // Toggles displaying percentage in the title bar (possible values - true, false, 'force')
});
```

### Browser Support

Piecon has been tested to work completely in the following browsers (older versions may be supported, but haven't been tested):

* Chrome 15+
* Firefox 9+
* Opera 11+

Currently the library falls back to title updates for the following browsers:

* Internet Explorer 9
* Safari 5+

Piecon is retina compatible so you can enjoy pixel-perfect crisp graphics.

## License

Licensed under the [MIT license](http://en.wikipedia.org/wiki/MIT_License).

## Credits

Piecon was inspired by Tom's [Tinycon](https://github.com/tommoor/tinycon).

