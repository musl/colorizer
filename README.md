Colorizer
=========

<https://code.hix.io/public/colorizer>

Color certain parts of text in certain buffers based on rules.

Options
-------

`plugins.var.ruby.colorizer.buffer_regex`

Buffers with names matching this regex are colorized. All buffers are
colorized if this option is empty.

`plugins.var.ruby.colorizer.rule.count`

This is the maximum number of rules to load.

`plugins.var.ruby.colorizer.rule.X`

X is zero or a positive integer. Rules are strings consisting of a regular
expression followed immediately by a slash and a Weechat color name. The
regular expressions are case-insensitive.

Text matching the regular expression is colored with the given color. The
last match "wins" and overlapping matches are not detected.

For example: "strelka|mongrel2/lightgreen"

