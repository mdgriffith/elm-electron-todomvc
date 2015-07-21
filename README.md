# TodoMVC in Elm using Electron - 

Run Elm in [Electron](http://electron.atom.io/)

Specifically this is a fork of [TodoMVC in Elm](https://github.com/evancz/elm-todomvc) that has been modified to run in Electron.

First you must have the [elm platform](http://elm-lang.org/install) installed as well as [electron](http://electron.atom.io/).

# Running the thing
First, you have to compile the elm file into javascript. Change to project root directory and run:
```bash
elm-make src/Todo.elm
```

Then run electron.
```bash
electron ../elm-electron-todomvc/
```



