### package prune

A nodejs tool to find unneeded package.json imports.

Searches all .js sources for require statements, reads in the local package.json, and produces a list of packages which are listed in package.json but never ```required()``` in any of the sources.

Does not modify any files. The aim of this package is to provide a list which should be audited.
