
# JADE example

The base functionality of HtmlCompiler is to compile HTML files to HTML files.
However, it is also possible to compile a number of templates first.

This example shows how to use HtmlCompiler to turn jade files into compiled HTML.

The jade template engine (Jade4J) will run first, the output of which will be
processed by HtmlCompiler to create the final result.