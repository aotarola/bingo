# Bingo+ !
Bingo app, originally made from [pragmaticstudio](https://pragmaticstudio.com/elm) excellent Elm course.

The idea behind this, is to learn Elm language and add new features on Bingo app while at it ( that's why the plus :D ).

## How to run

1.- Let's start by downloading elm packages

```bash
elm-package install
```

2.- Now we need to download `Grunt` and compile elm files

```bash
npm install -g grunt-cli --save-dev
npm install
grunt elm
```

3.- Start watching the changes!

```bash
grunt watch
```

4.- Open the `index.html` file in a browser and start playing Bingo!
