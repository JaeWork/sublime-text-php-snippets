sublime-text-php-snippets
=========================

Sublime Text PHP Snippets

The idea behind this repository is that we end up with a set of useful php snippets for quickly doing the day to day tasks. keywords should be as small as possible while remaining memorable. 

A list of keywords, descriptions and usage will appear here very (very) soon, along with the code to keep them up to date. If you have any snippets you think should be included then please submit them via pull request.

Found this repository with an inspiring implementation of text processing on the fly. https://github.com/akrabat/sublime-akrabat

looking deeper in the snippets documentation http://docs.sublimetext.info/en/latest/extensibility/snippets.html 
we see that perl regex and substitution is in effect. And that expressions can be nested! This means it should be possible to perform plural expressions as a nested or statement.

[Boost regex] http://www.boost.org/doc/libs/1_44_0/libs/regex/doc/html/boost_regex/syntax/perl_syntax.html
[Boost format] http://www.boost.org/doc/libs/1_44_0/libs/regex/doc/html/boost_regex/format/perl_format.html

TODO
----
Take a closer look at the gsa array command and get the plural converted to singular for

|| Name || Plural || Singular ||
| $items | getItems | addItem |
| $entries | getEntries | addEntry |