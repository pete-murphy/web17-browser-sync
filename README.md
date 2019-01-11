# Example use of `browser-sync`

**Note:** This assumes you have [Node](https://nodejs.org/en/) installed.

## Instructions

Copy the `package.json` file into the root directory of your Lambda School projects (assuming you have all your LS projects in one directory). Then run

```bash
$ npm i
```

You can start up a server with

```bash
$ npm start
```

This will give you a live server that hot-reloads any time an `html` or `css` file is saved in any of the subdirectories.


![Terminal](img/terminal.png)

<<<<<<< HEAD
Now you can navigate to `http://10.0.0.XX:3000` (whatever is displayed under `External`) to see your project.

![Animation](img/sequence.gif)

**Bonus:** You can open this address in your phone, tablet, laptop, and desktop&mdash;all at once if you want&mdash;and it will keep all in sync.

Check out `browser-sync` for more info: https://www.browsersync.io.
