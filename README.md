wak-odbc
========

Wakanda module to use ODBC.

About
-----
System worker binding to call the [unixODBC](http://www.unixodbc.org) library. The executable was compiled using libodbc 2.3.2, for Mac OS X (x64), Linux (x64) and Windows (x64).

![obsolete-word-black-frame-word-obsolete-word-black-frame-d-rendering-123942590](https://user-images.githubusercontent.com/1725068/78463940-29122280-771e-11ea-8be8-a7830725403e.jpg)

Old Wakanda.

Install
-------
Please read [install](https://github.com/miyako/wak-ftp/blob/master/install.md).

Example
-------
```
var modulesFolder = FileSystemSync('Modules');
var odbc = require(modulesFolder.path + 'odbc');

var code = '-b';

odbc.sql(code);
```


