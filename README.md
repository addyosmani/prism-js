# &lt;prism-js&gt;

A [Polymer](http://www.polymer-project.org) element for syntax highlighting with [Prism.js](http://prismjs.com/)

> Maintained by [Addy Osmani](https://github.com/addyosmani).

## Demo

> [Check it live](http://addyosmani.github.io/prism-js).

## Install

Install with [Bower](http://bower.io):

```sh
$ bower install --save prism-js
```

## Usage

1. Import Web Components' polyfill:

```html
<script src="platform.js"></script>
```

2. Import Custom Element:

```html
<link rel="import" href="prism-js.html">
```

3. Start using it!

```html
<prism-js language="javascript">
	Your code goes here
</prism-js>
```

## Examples


## Setup

In order to run it locally you'll need a basic server setup.

1. Install [Node.js](http://nodejs.org/download/)
2. Install [Grunt](http://gruntjs.com/):

    ```sh
    $ npm install --global grunt-cli
    ```

3. Install local dependencies:

    ```sh
    $ npm install
    ```

4. Run a local server and open `http://localhost:8000`.

    ```sh
    $ grunt connect
    ```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`language`      | *string*                  | `*`               | the language to highlight
`linenumbers`      | *boolean*                  | `false`               | display line numbers
`escape`      | *boolean*                  | `false`               | auto-escape/encode HTML for you using he.js

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/addyosmani/prism-js/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
