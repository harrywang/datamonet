# Collection of Generative Arts

This repo shows my curated collection of generative arts. You can find the source of the artwork in the README.md in each folder. 


# Setup

I use Canvas-Sketch framework in this project.

You can install the framework as follows:

```
$ git clone https://github.com/mattdesl/canvas-sketch
$ cd canvas-sketch
$ npm install canvas-sketch-cli -g
```

Each artwork has it's own folder in this repo. You can start a new artwork by：
```
$ mkdir exercises
$ canvas-sketch exercises/exercise1.js --new --open
```
A new file exercise1.js is created and a local web server is started to view the artwork.

To open existing artwork:
```
$ canvas-sketch canvas-sketch-examples/animated-p5.js --open
```

To develop with "Hot Reloading" instead of full page reload:
```
$ canvas-sketch canvas-sketch-examples/animated-p5.js --open --hot
```

Build your sketch to a sharable HTML + JS website
```
$ mkdir exercises/website/
$ cd exercises/website/
$ canvas-sketch ../exercise1.js --build
```
Then, `exercise1.html`, `exercise1.js`, `exercise1.js.map` are generated.
