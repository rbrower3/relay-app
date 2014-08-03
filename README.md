## A mobile app for tracking team progress during long-distance relay races

### to get up and, ahem, <em>running</em>...

You'll need node.js and the ionic package and bower

```bash
$ npm install -g ionic bower
```

Clone this repo, cd into `relay` and run:

```bash
$ ionic lib update
$ bower install
```

configure the platforms you want to use:

(substitute android for ios if not on a Mac, but if you can, the ios development
toolchain is a lot easier to work with until you need to do anything
custom to Android.)

```bash
$ ionic platform add ios
```

build & emulate:
```bash
$ ionic build ios
$ ionic emulate ios
```

or to use/view in a web browser

```bash
$ ionic serve
```



### Issues
make some and help work them!
