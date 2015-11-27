LayoutManagerDemo
=================

ABOUT:

 This application demonstrates interrogating the layout manager for information about   text layout, and the use of temporary attributes to color text.  Specifically, we    provide rollover coloring of text--one color for the line, another for the word,    and a third for the character under the mouse.  A subclass of NSTextView is used,   but solely for the purpose of obtaining mouse events.  The interesting portion of    the code involves the conversion of mouse coordinates to a particular glyph and   character index, then determining the corresponding line and word, and finally    using temporary attributes for coloring. 

===========================================================================
BUILD REQUIREMENTS:

Xcode 3.2, Mac OS X 10.6 Snow Leopard or later

===========================================================================
RUNTIME REQUIREMENTS:

Mac OS X 10.6 Snow Leopard or later

===========================================================================
CHANGES FROM PREVIOUS VERSIONS:

Version 1.1
- Project updated for Xcode 4.
Version 1.0
- First version.

===========================================================================
Copyright (C) 2001-2011 Apple Inc. All rights reserved.