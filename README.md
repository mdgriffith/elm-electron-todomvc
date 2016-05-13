# TodoMVC in Elm using Electron (updated for Elm 0.17) - 

Run Elm in [Electron](http://electron.atom.io/)!

Electron is a way to package web apps into a cross platform desktop application and Elm is a fascinating new way of writing front end code.  

You must have the [elm platform](http://elm-lang.org/install) installed as well as [electron](http://electron.atom.io/).

# Running the thing
Compile the elm file into javascript. 
```bash
elm-make Todo.elm --output elm.js

```

Then run electron on the current directory.
```bash
electron .
```


