
`clip8dependencies`
===================

Use `browserify` to generate `clip8dependencies.js` for static browser-side use in `clip_8`.

It is a separate project to keep the strictly browser-side `clip_8` project clear of any additional JS overhead.

prerequisites
-------------

+ npm

+ on linux it also wanted
```sudo apt install nodejs-legacy```


build a static bundle
---------------------

```npm run build```

'install'
---------

+ just copy `clip8dependencies.js` to a reasonable location in `clip_8` project dir

+ put it under version control there (so that clip_8 can be stand alone)

+ Update here and there if you feel like it :-)
