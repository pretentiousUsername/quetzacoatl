# Quetzalcoatl
> A pandoc template for everyday typesetting.

The original pandoc template is, by most respects, *passable*, but not
exactly great; it's mediocre at best. So, I went ahead and made a template
for myself. It's nothing fancy---there isn't any beamer functionality or
anything built into it, and I'm yet to define a color palette for it---but
overall it's useable.

More work is needed, but, for now, it works.

## List of parameters
| Parameter | Function | Value |
|:----------|:---------|:------|
| `paperSize` | changes paper size | Standard paper sizes |
| `twoSided` | makes the page double-sided | `true` or `false` |
| `titlepage` | adds a titlepage | `true` or `false` |
| `customTitle` | uses a custom title fomat (by yours truly) | `true` or `false` |
| `customType` | uses custom typefaces input by the user | see `quetzacoatl.tex` |
| `useEndnotes` | use endnotes instead of footnotes | `true` or `false` |
| `language` | sets the documents language | name of a language (defaults to English) |
| `fullpage` | uses the *whole* page of a document | `true or false` |
| `lineno` | adds line numbers to the text | `true` or `false` |
| `lineStretch` | sets line spacing | Float |
| `draft` | gives the document a draft watermark | `true` or `false` |
| `geometry` | sets up page geometry | see the LaTeX `geometry.sty` documentation |
| `listings` | uses the `listings` package | `true` or `false` |
| `linkAsNotes` | uses footnotes instead of hotlinks for URLs | `true` or `false` |
| `numberSections` | number sections in the document | `true` or `false` |
| `verbatimInNote` | allows verbatim text in footnotes | `true` or `false` |
| `title` | document title | text |
| `author` | document author | text/your name |
| `date` | date | yyyy-mm-dd preferably |
| `headerIncludes` | put stuff in the header | text |
| `sansTitle` | makes the title sans serif | `true` or `false` |
| `parIndent` | sets the paragraph indentation | float |
| `raggedLines` | Uses ragged instead of justified paragraphs |`EXPERIMENTAL - DON'T USE`|
| `parSpacing` | sets the length between paragraphs | float |
| `includeAtPreamble` | put whatever you want in the preamble | TeX code |
| `abstract` | your document abstract | text |
| `tableOfContents` | include table of contents in your document | `true` or `false` |



## Dependencies
* TeXlive or MikeTeX (a full installation is expected, but not necessary)

* Pandoc


## TODO
* Make a custom titlepage.

* ~~Fix the overall geometry of the output pdf---it feels a bit fishy for
whatever reason.~~

* ~~Work on an XCharter otf mathfont. (*Kill me.*)~~

> In some good news, an [XCharter math typeface][xcMath] has *finally*
> been made---and I didn't even have to do anything. Huge thanks to
> Daniel Flipo for his work on the typeface. It's not perfect yet, but
> it's a dramatic improvement from what I previously had to work with.

[xcMath]: https://ctan.org/tex-archive/fonts/xcharter-math

* Fix spacing issues with the quotes and tables.

* Write comprehensive documentation covering each variable/feature of the
template.

