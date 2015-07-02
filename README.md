[![view on npm](http://img.shields.io/npm/v/command-line-args.svg)](https://www.npmjs.org/package/command-line-args)
[![npm module downloads per month](http://img.shields.io/npm/dm/command-line-args.svg)](https://www.npmjs.org/package/command-line-args)
[![Build Status](https://travis-ci.org/75lb/command-line-args.svg?branch=rewrite)](https://travis-ci.org/75lb/command-line-args)
[![Dependency Status](https://david-dm.org/75lb/command-line-args.svg)](https://david-dm.org/75lb/command-line-args)

# command-line-args
Collect command-line options, generate a usage guide..

- Support most option notation styles
    - long options (`--find lib.js`)
    - short options (`-f lib.js`)
    - getopt-style combinations (`-xvf  lib.js`)
    - option=val style (`--find=lib.js`)
- Customisable usage guide generator
- Modular - define reusage option sets.
- Split options into groups, for apps with a large set of options.
- Fine control over validation, type

## Install
```sh
$ npm install command-line-args --save
```


## API Reference
<a name="exp_module_command-line-args--CliArgs"></a>
### CliArgs(definitions, argv) ⇒ <code>object</code> ⏏
**Kind**: Exported function  

| Param | Type |
| --- | --- |
| definitions | <code>module:command-line-args.argDefType</code> | 
| argv | <code>Array.&lt;string&gt;</code> | 


* * *

&copy; 2015 Lloyd Brookes \<75pound@gmail.com\>. Documented by [jsdoc-to-markdown](https://github.com/75lb/jsdoc-to-markdown).
