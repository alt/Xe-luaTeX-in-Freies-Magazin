# Article about Xe/LuaTeX

## This is a draft for an article about the modern engines XeTeX and LuaTeX for ”Freies Magazin“ written in german.

The main author is [Arno Trautmann](http://github.com/alt/Xe-luaTeX-in-Freies-Magazin)

## How to compile

As the ”Freies Magazin“ wants to have only-text document for proofreading, we need a textfile. As I rather read TeX’ed documents, I try a little hack: In line 5, there is an \iftrue/\iffalse. Change this to either get a nicely formatted pdf or an only-text file.

The document has to be compiled using the XeLaTeX format.
