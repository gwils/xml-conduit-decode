# xml-conduit-decode

Support for historical cursors & decoding on top of xml-conduit. Created in the sprit of scalaz-xml so that we can get useful context out of xml decoding failures.

We're using this in production to interact with a monstrous vendor SOAP API, so it should work for you if you're desperate for something like this (like I was faced with the job of taming such a SOAPY beast).

See the tests for an example of what this does.
