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
- font and text related elements (and their attributes): `<font/>`, `<font-face/>`, `<font-face-format/>`, `<font-face-name/>`, `<font-face-uri/>`, `<glyph/>`, `<hkern/>`, `<vkern/>`, `<missing-glyph/>`, `<altGlyph/>`, `<altGlyphDef/>`, `<altGlyphItem/>`, `<glyphRef/>`, `<tref/>`, `<tspan/>`
- general purpose elements : `<desc/>`, `<metadata/>`, `<title/>`, `<defs/>`, `<symbol/>`, `<switch/>`, `<script/>`, `<foreignObject/>`


### TODO

A lot :)

- <del>text (font-*, text*), color (gradients), stops, patterns</del>, markers and animation (not SMIL) elements
- <del>generic elements like `<metadata/>` and `<title/>`</del>
- <del>snippets for `<!DOCTYPE>`s, `CDATA` section and new SVG document template</del>
- support for `style` attribute on elements
- <del>general elements like `<foreigObject/>`, `<switch/>`, `<script/>`</del>
- complete attribute support for already implemented elements
- filters
- masks, clipPaths
- cursor
- support for SMIL


### Installation using Git

Open Terminal.app

	cd ~/Library/Application\ Support/Espresso/Sugars/
	git clone git://github.com/sdussaut/SVG.sugar.git



### Manual installation

- Download the source code and uncompress it.
- Rename the folder to `SVG.sugar` and put it in `HomeFolder/Library/Application Support/Espresso/Sugars/`.
- Enjoy!



### SVG Snippets
I wrote a few snippets to help with scary SVG stuff: `<!DOCTYPE>` declaration and `CDATA` sections. I also provide a basic SVG template to get you started.

All snippets are available in the toolbar and in the Actions menu (under the SVG category). They also come with a handy text trigger (activated with the tab key). Here is the list:

- Insert SVG 1.0 Doctype: `svgdoc10`
- Insert SVG 1.1 Basic Doctype: `svgdocbasic`
- Insert SVG 1.1 Full Doctype: `svgdoc11`
- Insert SVG 1.1 Tiny Doctype: `svgdoctiny`
- Insert `CDATA` section: `cdata`
- Invoking new basic SVG template: `newsvgdoc`

