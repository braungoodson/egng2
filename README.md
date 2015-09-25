# egng2
examples of angular2 apps

# usage
install dependencies, install the type definitions, install the compiler, run it

    $ npm install -g tsd@latest
    $ tsd install angular2 es6-promise rx rx-lite
    $ touch index.html app.ts
    $ npm install -g typescript@latest
    $ tsc --watch -m commonjs -t --emitDecoratorMetadata app.ts

then begin writing your typescript
