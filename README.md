### spawn & exec (child_process)

Simple reminder of syntax for Node's `child_process` methods `spawn` and `exec`.

`curl.js` compares downloading a file with Node's own `http.get` (no https: on this one), `child_process.spawn` (allows us to pass CLI args in node; returns a Stream and `child_process.exec` (returns a Buffer).

