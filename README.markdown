# LaTeX Styles

Many who have seen my LaTeX-generated documents have commented that “they don't look like LaTeX”.
That’s because LaTeX is just an engine, you drive it as you want it.
There’s no reason a LaTeX document must be typeset in Computer Modern fonts, or have exactly one font all throughout the document.

## Typography

### OpenType Fonts

Computer Modern is not really all that modern in 2009 — not to mention, restrictive in terms of choice.
With the plethora of fonts available to you via OpenType fonts (on Mac OS X, Windows and Linux), there is no reason not to use them in LaTeX documents.
Combine the advanced typesetting features and document management features of LaTeX with the typographic quality of OpenType fonts from reputed foundries.

This style requires the [XeTeX](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=xetex) engine on Mac OS X, and will not work with pdfTeX or any other variant.

### Sans Serif Titles

Best used in combination with the OpenType fonts style.
Serif fonts are preferred for longer passages of text because of the readability advantages of the serifs (they guide the eye along from one character to the next, so you can glide along and read the text quicker.)
But there’s no harm in using sans-serif fonts for headlines, titles, and other areas where text is short.
This adds a bit of elegance and flavor to an otherwise drab document.

## Eco-friendly Draft Mode

LaTeX’s default margins lead to a lot of paper wastage when printed.
For quick drafts, it is often OK to reduce margins, and thereby print on fewer sheets of paper.

### 1 Inch Margins

Yes, the default margins in the LaTeX article document class have been designed with care.
The intention is to minimize the number of words per line, and thus make it easier on the eyes.
That's also why newspapers have columns.

But sometimes you really do want to override them, save paper, be nice to the environment, etc.

### Less Paper

If you want to be even more radical in saving paper and scoring extra points with the environment, this is your style. It squeezes your content as far as possible towards the margin, sacrificing readability in the process. But it does get the job done in fewer sheets of paper.
