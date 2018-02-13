CB-13797 Example
================

Steps to reproduce
------------------

```
npm install
./node_modules/.bin/cordova prepare --verbose
```

Notes
-----

* All dependencies are tracked **only** in package.json, not in config.xml
* Running `cordova prepare` will cause platforms/plugins to be added to
  config.xml, so make sure you're starting with no changes to that file
