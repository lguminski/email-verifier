## Change log

v1.3.2
----------
* Uses x/net/proxy to fix issue when using SOCKS5

v1.3.1
----------
* Fix a bug: `IsDisposable()` matches the complete email domain
* Update dependent metadata
* Update Dependencies

v1.3.0
----------
* Support setting SOCKS5 proxy to perform `CheckSMTP()`
* Make pkg compatible with earlier versions of Go

v1.2.0
----------
* Support adding custom disposable email domains 
* Fix a wrong reference in README 
* Update dependent metadata  
* Update Dependencies

v1.1.0
----------
* Performance optimization:
    * reduce Result struct size from 96 to 80
    * `ParseAddress()` return `Syntax` instead of reference, for reducing GC pressure and improve memory locality.
* Provide a simple API server
* Bugfix: gravatar images may not exist

v1.0.3
----------
* Add a New feature: domain suggestion (typo check)

v1.0.2
----------
* Add build metadata tools to generate metadata_*.go files 
* Update load meta data logic
