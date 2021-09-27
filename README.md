# QuickJS

===================================================================

Just 
```
git clone https://github.com/JavaScriptBench/quickjs.git
cd quickjs
git checkout b5e62895c619d4ffc75c9d822c8d85f1ece77e5b
make
./qjs examples/hello.js
```
Edit the top of the Makefile if you wish to select specific options then run `make`.

You can type `sudo make install` if you wish to install the binaries to /usr/local.

`b5e62895c619d4ffc75c9d822c8d85f1ece77e5b` for release version 2021-03-27


`qjsc` is the command line compiler:
```
./qjsc -o hello examples/hello.js
./hello
```













====================================================================

The main documentation is in doc/quickjs.pdf or doc/quickjs.html.
