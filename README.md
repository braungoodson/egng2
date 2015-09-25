# egng2
examples of angular2 apps

# usage
install dependencies, install the type definitions, install the compiler, run the compiler, install a http server, run the http server

    $ npm install -g tsd@latest
    $ tsd install angular2 es6-promise rx rx-lite
    $ touch index.html app.ts
    $ npm install -g typescript@latest
    $ tsc --watch -m commonjs -t --emitDecoratorMetadata app.ts
    $ npm install -g http-server

then begin writing your typescript
