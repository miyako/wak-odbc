wak-odbc
========

Wakanda module to use ODBC.

About
-----
System worker binding to call the [unixODBC](http://www.unixodbc.org) library. The executable was compiled using libodbc 2.3.2, for Mac OS X (x64), Linux (x64) and ~~Windows (x64)~~.

Remarks
-------
**Linux**: if you find that isql or iusql is raising the exception "/usr/local/lib/libreadline.so.6: undefined symbol: UP", you might want to apply [this](https://vkarthickeyan.wordpress.com/2012/02/16/mysql-symbol-lookup-error-usrlocalliblibreadline-so-6-undefined-symbol-up/) solution.
