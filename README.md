wak-odbc
========

Wakanda module to use ODBC.

About
-----
System worker binding to call the [unixODBC](http://www.unixodbc.org) library. The executable was compiled using libodbc 2.3.2, for Mac OS X (x64), Linux (x64) and Windows (x64).

Install
-------
Please read [install](install.md).

Example
-------
```
var modulesFolder = FileSystemSync('Modules');
var odbc = require(modulesFolder.path + 'odbc');

var code = '-b';

odbc.sql(code);
```


