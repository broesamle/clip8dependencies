
`clip8dependencies`
===================

Use `browserify` to generate `bundle.js` for static browser-side use in `clip_8`

It is a separate project to keep the strictly browser-side `clip_8` project clear of any additional JS overhead.

prerequisites
-------------

+ npm

+ on linux it also wanted
```sudo apt install nodejs-legacy```


build a static bundle
---------------------

```npm run build > bundle.js```

'install'
---------

+ just copy the file to a reasonable location in clip_8

+ put it under version control there (so that clip_8 can be stand alone)

+ Update there if you feel like it :-)
