[![Linux CI](https://github.com/flightaware/TclXML/actions/workflows/linux-ci.yml/badge.svg)](https://github.com/flightaware/TclXML/actions/workflows/linux-ci.yml)

I was able to clean compile, but several tests fail, for example destroying children still leaves items inside the tree.\
This package has then been replaced in favour of the tdom.

# TclXML
TclXML is a package that provides XML parsing for the Tcl scripting language.
It has two implementations of XML parsers: one written purely in Tcl
and a wrapper for the Gnome libxml2 C library.

The TclXML package now incorporates the TclDOM and TclXSLT packages.
TclDOM and TclXSLT were previously distributed as separate packages.
The three packages may still be used as if they were standalone.
