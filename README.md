# chai-register
Register hook for NodeJS [chai](https://github.com/chaijs/chai) package. Expose `assert` and `expect` functions globally.

## Install
```
npm i -D chai-register
```

## Usage
Now you can simple include line below in your `mocha.opts` file:
```
--require chai-register
```

### NOTE: Chai package is not included here, supposed that `chai` is installed to your project deps
