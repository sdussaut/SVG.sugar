# SVG Sugar for Espresso text editor

SVG sugar for Espresso aims at adding support for SVG completion. A lot still has to be done. :)


For the moment the sugar proposes a basic level of SVG completion support. Are supported:

- basic primitives : `<circle/>`, `<ellipse/>`, `<rect/>`, `<line/>`, `<path/>`, `<polygon/>`, `<polyline/>`, `<text/>`, `<image/>`
- most basic attributes:
	- coordinates
	- width
	- height
	- fill
	- stroke
	- display
	- opacity
	- transform
	- event attributes
	- document event attributes (for `<svg/>` element)
- `<svg/>` element
- `<g/>` and `<use/>` elements


### TODO

A lot :)

- text (font-*, text*), color (gradients), markers and animation (not SMIL) elements
- support for `style` attribute on elements
- general elements like `<foreigObject/>`, `<switch/>`, `<script/>`
- complete attribute support for already implemented elements
- filters
- support for SMIL


### Installation using Git

Open Terminal.app

	cd ~/Library/Application\ Support/Espresso/Sugars/
	git clone git://github.com/sdussaut/SVG.sugar.git



### Manual installation

- Download the source code and uncompress it.
- Rename the folder to `SVG.sugar` and put it in `HomeFolder/Library/Application Support/Espresso/Sugars/`.
- Enjoy!