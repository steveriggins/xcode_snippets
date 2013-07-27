xcode_snippets
==============

This repository stores Xcode snippets that I use on a daily basis.

installation
============

Copy the snippet files into ~/Library/Developer/Xcode/UserData/CodeSnippets/

weakify_strongify_snippets
==========================

We have macros @weakify and @strongify that take a variable parameter.  The snippets in this folder include:

* @ws expands into @weakify(self);
* @ss expands into @strongify(self);
* @wv expands into @weakify(variable_placeholder);
* @sv expands into @strongify(variable_placeholder);

See https://github.com/jspahrsummers/libextobjc for the @weakify and @strongify macros
