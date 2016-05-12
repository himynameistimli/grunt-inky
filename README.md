# grunt-inky

> A grunt plugin for ZURB Inky. https://github.com/zurb/inky

## Getting Started
This plugin requires Grunt `>=0.4.0`

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install grunt-inky --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-inky');
```

## The "inky" task

### Overview
In your project's Gruntfile, add a section named `inky` to the data object passed into `grunt.initConfig()`.

```js
grunt.initConfig({
    inky: {
        base: {
            options: {
                // your options
            },
            files: {
                'dest/index.html': ['src/index.html'],
            }
        }
    }
});
```

### Options

#### options.columnCount
Type: `Number`
Default value: `12`

Column count for the grid. Make sure your Foundation for Emails project has the same column count in the Sass as well.

#### options.components
Type: `Object`
Default value: 
```json
{
    button: 'button',
    row: 'row',
    columns: 'columns',
    container: 'container',
    inky: 'inky',
    blockGrid: 'block-grid',
    menu: 'menu',
    menuItem: 'item'
}
```

Tag names for custom components. See [Inky Docs for custom elements](https://github.com/zurb/inky#custom-elements)

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Lint and test your code before submitting a pull request.

***

## Thanks

grunt-inky was created and is maintained by [Michael Worm](https://github.com/Miw0).