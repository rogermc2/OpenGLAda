---
layout : default
title : API - FTGL
packages : FTGL
api : true
permalink: ftgl.html
---

# The FTGL binding

FTGL is a small library for rendering text in OpenGL. It uses FreeType2 and
is able to use TrueType fonts. This binding is not complete, because a
complete binding would also need to provide parts of the FreeType2 API.

Currently, there is only the package `FTGL.Fonts` available, which enables
you to load fonts and render text with them. Handling of single glyphs has
not been wrapped, nor have the layouting features.

This binding requires the FTGL library on your system.

 [1]: http://www.niestu.com/software/lumen/