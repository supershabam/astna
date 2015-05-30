# problem statement:

It is difficult to know what open source javascript libraries are in use by major websites because production websites often bundle or obfuscate their javascript. I would like to be able to idenfity if an open source library is likely used in a bundled piece of javascript.

# to test:

[ ] will a minified jQuery AST look similar to a full text AST of jQuery
[ ] will a bundle that includes other libs and also jQuery have a portion of its AST that looks like the AST of jQuery
