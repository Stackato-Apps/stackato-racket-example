HPE Helion Stackato Racket Example
==================================

This example uses the buildpack
https://github.com/drautb/heroku-buildpack-racket

Steps for running this example
------------------------------

```
$ stackato target <VM URL>
$ stackato login <first user username>
Password: *******
$ git clone <this git repo>
$ cd stackato-racket-example/
$ stackato push --no-prompt
$ stackato open
```

This last line with open the app in your browser.
