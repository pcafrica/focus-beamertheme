# Focus v2.9.0
A presentation theme for LaTeX Beamer that aims at a clean and minimalist design,
so to minimize distractions and put the focus directly on the content.

This package is available through the [CTAN](https://ctan.org/pkg/beamertheme-focus) in
most LaTeX distributions such as [MiKTeX](https://ctan.org/pkg/miktex) and [TeXLive](https://ctan.org/pkg/texlive).

Requires the packages [appendixnumberbeamer](https://ctan.org/pkg/appendixnumberbeamer),
[fira](https://ctan.org/pkg/fira) and [PGF/TikZ](https://ctan.org/pkg/pgf)
to be installed in your LaTeX distribution.

Demo
----
A full demo is available. Refer to `focus-demo.tex` and `focus-demo.pdf`.

![](https://github.com/elauksap/focustheme/blob/master/focus-demo/demo-titlepage.jpg)
![](https://github.com/elauksap/focustheme/blob/master/focus-demo/demo-subsectionpage.jpg)
![](https://github.com/elauksap/focustheme/blob/master/focus-demo/demo-typeset.jpg)
![](https://github.com/elauksap/focustheme/blob/master/focus-demo/demo-focus.jpg)
![](https://github.com/elauksap/focustheme/blob/master/focus-demo/demo-references.jpg)
![](https://github.com/elauksap/focustheme/blob/master/focus-demo/demo-appendix.jpg)

Download
========
Download the latest release by following [this](https://github.com/elauksap/focustheme/releases) link.

Instructions
============
After downloading, copy the files named beamer*themefocus.sty into the same folder as your LaTeX source file.

Then include the theme by writing:
```latex
\documentclass{beamer}

\usetheme{focus}
```
in the preamble of your document.

Customize colors
----------------
Focus is based on two colors, namely `main` and `background`, that can be customized after including the theme.

For example:
```latex
\usetheme{focus}

\definecolor{main}{RGB}{92, 138, 168}
\definecolor{background}{RGB}{240, 247, 255}
```
produces the following ice-blue color theme.

![](https://github.com/elauksap/focustheme/blob/master/focus-demo/demo-titlepage-color.jpg)

Customize the footline
----------------------
The footline numbering can be customized through the theme option _numbering_. The standard value is:
```latex
\usetheme[numbering=progressbar]{focus}
```
that shows an progress bar of increasing length on the footline.

Alternatively, a full footline bar with the frame numbering can be shown with:
```latex
\usetheme[numbering=fullbar]{focus}
```
In such case, an optional text to be printed on the left side of the footline
can be customized with:
```latex
\footlineinfo{Custom footline text}
```

The footline may also be disabled globally by typing:
```latex
\usetheme[numbering=none]{focus}
```

Customize fonts
---------------
Focus is using the [Fira fonts](https://bboxtype.com/typefaces/FiraSans/) by default.

This can be changed by using the option _nofirafonts_:
```latex
\usetheme[nofirafonts]{focus}
```

License
=======
This software is released under the [GNU GPL v3.0 License](https://www.gnu.org/licenses/gpl-3.0.en.html).

Contacts
========
If you are enjoying this theme please share it with your friends or colleagues!

Any suggestions, comments, criticism or appreciation are welcome!

Contact information are available to registered users on my Github profile page.

Contributors
============
Focus was initially created and designed by [Pasquale Africa](https://github.com/elauksap).

The following people deserve appreciation and acknowledgment for improving the template with
additions and modifications (in alphabetical order):

- Sebastian Friedl
- Benjamin Goldman

A more detailed contribution list is found [here](https://github.com/elauksap/focus-beamertheme/graphs/contributors).
