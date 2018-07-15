# Focus
A presentation theme for LaTeX Beamer that aims at a clean and minimalist design,
so to minimize distractions and put the focus directly on the content.

This package is available through the [CTAN](https://ctan.org/pkg/beamertheme-focus) in
most LaTeX distributions such as [MiKTeX](https://ctan.org/pkg/miktex) and [TeXLive](https://ctan.org/pkg/texlive).

Requires the packages [appendixnumberbeamer](https://ctan.org/pkg/appendixnumberbeamer),
[fira](https://ctan.org/pkg/fira) and [PGF/TikZ](https://ctan.org/pkg/pgf)
to be installed in your LaTeX distribution.

Demo
----
A full demo is available. Refer to `demo.tex` and `demo.pdf`.

![](https://github.com/elauksap/focustheme/blob/master/demo-screenshots/demo-titlepage.jpg)
![](https://github.com/elauksap/focustheme/blob/master/demo-screenshots/demo-sectionpage.jpg)
![](https://github.com/elauksap/focustheme/blob/master/demo-screenshots/demo-typeset.jpg)
![](https://github.com/elauksap/focustheme/blob/master/demo-screenshots/demo-focus.jpg)
![](https://github.com/elauksap/focustheme/blob/master/demo-screenshots/demo-references.jpg)
![](https://github.com/elauksap/focustheme/blob/master/demo-screenshots/demo-appendix.jpg)

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

![](https://github.com/elauksap/focustheme/blob/master/demo-screenshots/demo-titlepage-color.jpg)

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

The footline may also be disabled by typing:
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

Authors
=======
Focus was initially created and designed by [Pasquale Africa](https://github.com/elauksap).

My gratitude goes to the following authors, whose help has provided a significant contribution
to its development.

[Sebastian Friedl](https://github.com/SFr682k)
