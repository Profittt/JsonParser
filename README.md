JsonParser
==========

Recursive descent JSON parser for PascalScript

I translated [Douglas Crockford's recursive descent parser](https://github.com/douglascrockford/JSON-js) into [PascalScript](http://www.remobjects.com/ps.aspx). Since PascalScript doesn't handle pointers and classes, I used dynamic arrays to store JSON values in a type-safe way. The parser can also be used from Standard Pascal or Object Pascal (Delphi), but since these don't suffer from the constraints of PascalScript, other parsers may be more efficient (see [here](http://json.org) and [here](http://blog.synopse.info/post/2011/06/02/Fast-JSON-parsing)). If you need to parse JSON strings from PascalScript, the best option is to add one of the fast parsers to the host code, and make it accessible from script code. This implementation is for those who don't have access to the host code. 

The JSON testfiles contain the examples from [here](http://json.org/example). 

This code is in the Public Domain.
NO WARRANTY EXPRESSED OR IMPLIED. USE AT YOUR OWN RISK.
