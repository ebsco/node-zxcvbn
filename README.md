# node-zxcvbn

[zxcvbn](https://github.com/lowe/zxcvbn) password strength calculator, published
as a node.js module.

Authored by Dan Wheeler at Dropbox. Published to npm by Michael Smith.

See [the original](https://github.com/lowe/zxcvbn) for more details.

This package builds both with npm and bower.
--------------------------------------------

####Bower (bower.json):

```
"zxcvbn": "https://github.com/buttercoin/node-zxcvbn.git#master"
```

####NPM (package.json):

```
"zxcvbn": "git://github.com/buttercoin/node-zxcvbn.git#master"
```

#####You will likely need to fork this repo due to the hardcoded path to zxcvbn.js present in zxcvbn-async.js

If your zxcvbn.js file is not located at public/javascripts/vendor/zxcvbn.js, follow these steps:

1. Fork the repo (make sure you change your package links to your new location)
2. Edit zxcvbn/async.coffee with the correct location of the zxcvbn.js file
3. Run these commands:  
   $ cd zxcvbn  
   $ ./compile_and_minify.sh
4. Push the resulting changes back to your new repository
