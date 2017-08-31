# lumo-practice
A project of lumo for my practice about clojurescript.

# Setup
## lumo
Install [lumo](https://github.com/anmonteiro/lumo).

## dependencies
```
npm install
```
# Run
## Hello world
```
lumo -c src -m hello-world.core
```

## Express sample app
```
lumo -c src -m express-sample.core
```

Then access to http://localhost:3000

# Build
## Hello world
```
lumo -c src build_hello_world.cljs
```
Then
```
node index_hello_world.js
```

## Express sample app
```
lumo -c src build_express_sample.cljs
```
Then
```
node index_express_sample.cljs
```

# References
- [lumo-npm-example](https://github.com/rberger/lumo-npm-example)
- [express hello world example](https://expressjs.com/en/starter/hello-world.html)
