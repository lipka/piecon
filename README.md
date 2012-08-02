# Piecon

Pie charts in your favicon!

A tiny javascript library for dynamically generating pie charts in your favicons.

<img src="https://github.com/lipka/piecon/blob/master/example/screenshot.png?raw=true">

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
  background: '#bbb', // Empty pie chart part color
  shadow: '#fff', // Ring shadow color
  fallback: false' // Toggles displaying percentage in the title bar (possible values - true, false, 'force')
});
```

## License

Licensed under the [MIT license](http://en.wikipedia.org/wiki/MIT_License).

## Credits

Piecon was inspired by [Tinycon](https://github.com/tommoor/tinycon).

## An Lipka project

Made by yours truly - [@lipka](https://github.com/lipka).
