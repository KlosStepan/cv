## Arch Installation w/ marvosym.sty fix
```
[stepo@archlinux cv]$ sudo pacman -S texlive-fontsrecommended
resolving dependencies...
looking for conflicting packages...

Packages (1) texlive-fontsrecommended-2025.2-1

Total Download Size:    89.42 MiB
Total Installed Size:  148.98 MiB

:: Proceed with installation? [Y/n] Y
:: Retrieving packages...
 texlive-fontsrecommended-2025.2-1-any            89.4 MiB  25.5 MiB/s 00:04 [###########################################] 100%
(1/1) checking keys in keyring                                               [###########################################] 100%
(1/1) checking package integrity                                             [###########################################] 100%
(1/1) loading package files                                                  [###########################################] 100%
(1/1) checking for file conflicts                                            [###########################################] 100%
(1/1) checking available disk space                                          [###########################################] 100%
:: Processing package changes...
(1/1) installing texlive-fontsrecommended                                    [###########################################] 100%
:: Running post-transaction hooks...
(1/4) Arming ConditionNeedsUpdate...
(2/4) Updating TeXLive filename database...
(3/4) Updating TeXLive format files...
(4/4) Updating TeXLive font maps...
[stepo@archlinux cv]$ kpsewhich marvosym.sty
/usr/share/texmf-dist/tex/latex/marvosym/marvosym.sty
[stepo@archlinux cv]$ pdflatex cv.tex
This is pdfTeX, Version 3.141592653-2.6-1.40.27 (TeX Live 2026/dev/Arch Linux) (preloaded format=pdflatex)
 restricted \write18 enabled.
entering extended mode
(./cv.tex
LaTeX2e <2024-11-01> patch level 2
L3 programming layer <2025-01-18>
(/usr/share/texmf-dist/tex/latex/base/article.cls
Document Class: article 2024/06/29 v1.4n Standard LaTeX document class
(/usr/share/texmf-dist/tex/latex/base/size11.clo))
(/usr/share/texmf-dist/tex/latex/base/latexsym.sty)
(/usr/share/texmf-dist/tex/latex/preprint/fullpage.sty)
(/usr/share/texmf-dist/tex/latex/titlesec/titlesec.sty)
(/usr/share/texmf-dist/tex/latex/marvosym/marvosym.sty)
(/usr/share/texmf-dist/tex/latex/graphics/color.sty
(/usr/share/texmf-dist/tex/latex/graphics-cfg/color.cfg)
(/usr/share/texmf-dist/tex/latex/graphics-def/pdftex.def)
(/usr/share/texmf-dist/tex/latex/graphics/dvipsnam.def)
(/usr/share/texmf-dist/tex/latex/graphics/mathcolor.ltx))
(/usr/share/texmf-dist/tex/latex/tools/verbatim.sty)
(/usr/share/texmf-dist/tex/latex/enumitem/enumitem.sty)
(/usr/share/texmf-dist/tex/latex/hyperref/hyperref.sty
(/usr/share/texmf-dist/tex/generic/iftex/iftex.sty)
(/usr/share/texmf-dist/tex/latex/graphics/keyval.sty)
(/usr/share/texmf-dist/tex/latex/kvsetkeys/kvsetkeys.sty)
(/usr/share/texmf-dist/tex/generic/kvdefinekeys/kvdefinekeys.sty)
(/usr/share/texmf-dist/tex/generic/pdfescape/pdfescape.sty
(/usr/share/texmf-dist/tex/generic/ltxcmds/ltxcmds.sty)
(/usr/share/texmf-dist/tex/generic/pdftexcmds/pdftexcmds.sty
(/usr/share/texmf-dist/tex/generic/infwarerr/infwarerr.sty)))
(/usr/share/texmf-dist/tex/latex/hycolor/hycolor.sty)
(/usr/share/texmf-dist/tex/latex/hyperref/nameref.sty
(/usr/share/texmf-dist/tex/latex/refcount/refcount.sty)
(/usr/share/texmf-dist/tex/generic/gettitlestring/gettitlestring.sty
(/usr/share/texmf-dist/tex/latex/kvoptions/kvoptions.sty)))
(/usr/share/texmf-dist/tex/latex/etoolbox/etoolbox.sty)
(/usr/share/texmf-dist/tex/generic/stringenc/stringenc.sty)
(/usr/share/texmf-dist/tex/latex/hyperref/pd1enc.def)
(/usr/share/texmf-dist/tex/generic/intcalc/intcalc.sty)
(/usr/share/texmf-dist/tex/latex/hyperref/puenc.def)
(/usr/share/texmf-dist/tex/latex/url/url.sty)
(/usr/share/texmf-dist/tex/generic/bitset/bitset.sty
(/usr/share/texmf-dist/tex/generic/bigintcalc/bigintcalc.sty))
(/usr/share/texmf-dist/tex/latex/base/atbegshi-ltx.sty))
(/usr/share/texmf-dist/tex/latex/hyperref/hpdftex.def
(/usr/share/texmf-dist/tex/latex/base/atveryend-ltx.sty)
(/usr/share/texmf-dist/tex/latex/rerunfilecheck/rerunfilecheck.sty
(/usr/share/texmf-dist/tex/generic/uniquecounter/uniquecounter.sty)))
(/usr/share/texmf-dist/tex/latex/fancyhdr/fancyhdr.sty)
(/usr/share/texmf-dist/tex/generic/babel/babel.sty
(/usr/share/texmf-dist/tex/generic/babel/txtbabel.def)
(/usr/share/texmf-dist/tex/generic/babel-english/english.ldf))
(/usr/share/texmf-dist/tex/generic/babel/locale/en/babel-english.tex)
(/usr/share/texmf-dist/tex/latex/tools/tabularx.sty
(/usr/share/texmf-dist/tex/latex/tools/array.sty))
(/usr/share/texmf-dist/tex/latex/todonotes/todonotes.sty
(/usr/share/texmf-dist/tex/latex/base/ifthen.sty)
(/usr/share/texmf-dist/tex/latex/xkeyval/xkeyval.sty
(/usr/share/texmf-dist/tex/generic/xkeyval/xkeyval.tex
(/usr/share/texmf-dist/tex/generic/xkeyval/xkvutils.tex)))
(/usr/share/texmf-dist/tex/latex/xcolor/xcolor.sty
(/usr/share/texmf-dist/tex/latex/graphics-cfg/color.cfg)
(/usr/share/texmf-dist/tex/latex/graphics/mathcolor.ltx))
(/usr/share/texmf-dist/tex/latex/pgf/frontendlayer/tikz.sty
(/usr/share/texmf-dist/tex/latex/pgf/basiclayer/pgf.sty
(/usr/share/texmf-dist/tex/latex/pgf/utilities/pgfrcs.sty
(/usr/share/texmf-dist/tex/generic/pgf/utilities/pgfutil-common.tex)
(/usr/share/texmf-dist/tex/generic/pgf/utilities/pgfutil-latex.def)
(/usr/share/texmf-dist/tex/generic/pgf/utilities/pgfrcs.code.tex
(/usr/share/texmf-dist/tex/generic/pgf/pgf.revision.tex)))
(/usr/share/texmf-dist/tex/latex/pgf/basiclayer/pgfcore.sty
(/usr/share/texmf-dist/tex/latex/graphics/graphicx.sty
(/usr/share/texmf-dist/tex/latex/graphics/graphics.sty
(/usr/share/texmf-dist/tex/latex/graphics/trig.sty)
(/usr/share/texmf-dist/tex/latex/graphics-cfg/graphics.cfg)))
(/usr/share/texmf-dist/tex/latex/pgf/systemlayer/pgfsys.sty
(/usr/share/texmf-dist/tex/generic/pgf/systemlayer/pgfsys.code.tex
(/usr/share/texmf-dist/tex/generic/pgf/utilities/pgfkeys.code.tex
(/usr/share/texmf-dist/tex/generic/pgf/utilities/pgfkeyslibraryfiltered.code.te
x)) (/usr/share/texmf-dist/tex/generic/pgf/systemlayer/pgf.cfg)
(/usr/share/texmf-dist/tex/generic/pgf/systemlayer/pgfsys-pdftex.def
(/usr/share/texmf-dist/tex/generic/pgf/systemlayer/pgfsys-common-pdf.def)))
(/usr/share/texmf-dist/tex/generic/pgf/systemlayer/pgfsyssoftpath.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/systemlayer/pgfsysprotocol.code.tex))
(/usr/share/texmf-dist/tex/generic/pgf/basiclayer/pgfcore.code.tex
(/usr/share/texmf-dist/tex/generic/pgf/math/pgfmath.code.tex
(/usr/share/texmf-dist/tex/generic/pgf/math/pgfmathutil.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/math/pgfmathparser.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/math/pgfmathfunctions.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/math/pgfmathfunctions.basic.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/math/pgfmathfunctions.trigonometric.code
.tex)
(/usr/share/texmf-dist/tex/generic/pgf/math/pgfmathfunctions.random.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/math/pgfmathfunctions.comparison.code.te
x) (/usr/share/texmf-dist/tex/generic/pgf/math/pgfmathfunctions.base.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/math/pgfmathfunctions.round.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/math/pgfmathfunctions.misc.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/math/pgfmathfunctions.integerarithmetics
.code.tex) (/usr/share/texmf-dist/tex/generic/pgf/math/pgfmathcalc.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/math/pgfmathfloat.code.tex))
(/usr/share/texmf-dist/tex/generic/pgf/math/pgfint.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/basiclayer/pgfcorepoints.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/basiclayer/pgfcorepathconstruct.code.tex
) (/usr/share/texmf-dist/tex/generic/pgf/basiclayer/pgfcorepathusage.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/basiclayer/pgfcorescopes.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/basiclayer/pgfcoregraphicstate.code.tex)

(/usr/share/texmf-dist/tex/generic/pgf/basiclayer/pgfcoretransformations.code.t
ex) (/usr/share/texmf-dist/tex/generic/pgf/basiclayer/pgfcorequick.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/basiclayer/pgfcoreobjects.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/basiclayer/pgfcorepathprocessing.code.te
x) (/usr/share/texmf-dist/tex/generic/pgf/basiclayer/pgfcorearrows.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/basiclayer/pgfcoreshade.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/basiclayer/pgfcoreimage.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/basiclayer/pgfcoreexternal.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/basiclayer/pgfcorelayers.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/basiclayer/pgfcoretransparency.code.tex)
 (/usr/share/texmf-dist/tex/generic/pgf/basiclayer/pgfcorepatterns.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/basiclayer/pgfcorerdf.code.tex)))
(/usr/share/texmf-dist/tex/generic/pgf/modules/pgfmoduleshapes.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/modules/pgfmoduleplot.code.tex)
(/usr/share/texmf-dist/tex/latex/pgf/compatibility/pgfcomp-version-0-65.sty)
(/usr/share/texmf-dist/tex/latex/pgf/compatibility/pgfcomp-version-1-18.sty))
(/usr/share/texmf-dist/tex/latex/pgf/utilities/pgffor.sty
(/usr/share/texmf-dist/tex/latex/pgf/utilities/pgfkeys.sty
(/usr/share/texmf-dist/tex/generic/pgf/utilities/pgfkeys.code.tex))
(/usr/share/texmf-dist/tex/latex/pgf/math/pgfmath.sty
(/usr/share/texmf-dist/tex/generic/pgf/math/pgfmath.code.tex))
(/usr/share/texmf-dist/tex/generic/pgf/utilities/pgffor.code.tex))
(/usr/share/texmf-dist/tex/generic/pgf/frontendlayer/tikz/tikz.code.tex
(/usr/share/texmf-dist/tex/generic/pgf/libraries/pgflibraryplothandlers.code.te
x) (/usr/share/texmf-dist/tex/generic/pgf/modules/pgfmodulematrix.code.tex)
(/usr/share/texmf-dist/tex/generic/pgf/frontendlayer/tikz/libraries/tikzlibrary
topaths.code.tex)))
(/usr/share/texmf-dist/tex/generic/pgf/frontendlayer/tikz/libraries/tikzlibrary
positioning.code.tex) (/usr/share/texmf-dist/tex/latex/tools/calc.sty))
(/usr/share/texmf-dist/tex/latex/l3backend/l3backend-pdftex.def)
No file cv.aux.
(/usr/share/texmf-dist/tex/context/base/mkii/supp-pdf.mkii
[Loading MPS to PDF converter (version 2006.09.02).]
) (/usr/share/texmf-dist/tex/latex/epstopdf-pkg/epstopdf-base.sty
(/usr/share/texmf-dist/tex/latex/latexconfig/epstopdf-sys.cfg))
(/usr/share/texmf-dist/tex/latex/base/ulasy.fd)

Package fancyhdr Warning: \footskip is too small (0.0pt):
(fancyhdr)                Make it at least 4.08003pt, for example:
(fancyhdr)                \setlength{\footskip}{4.08003pt}.

[1{/var/lib/texmf/fonts/map/pdftex/updmap/pdftex.map}{/usr/share/texmf-dist/fon
ts/enc/dvips/cm-super/cm-super-ts1.enc}] (./cv.aux)

Package rerunfilecheck Warning: File `cv.out' has changed.
(rerunfilecheck)                Rerun to get outlines right
(rerunfilecheck)                or use package `bookmark'.

 )</usr/share/texmf-dist/fonts/type1/public/amsfonts/cm/cmbx10.pfb></usr/share/
texmf-dist/fonts/type1/public/amsfonts/cm/cmbx12.pfb></usr/share/texmf-dist/fon
ts/type1/public/amsfonts/cm/cmbx6.pfb></usr/share/texmf-dist/fonts/type1/public
/amsfonts/cm/cmcsc10.pfb></usr/share/texmf-dist/fonts/type1/public/amsfonts/cm/
cmr10.pfb></usr/share/texmf-dist/fonts/type1/public/amsfonts/cm/cmsy10.pfb></us
r/share/texmf-dist/fonts/type1/public/amsfonts/cm/cmti10.pfb></usr/share/texmf-
dist/fonts/type1/public/cm-super/sfrm1095.pfb>
Output written on cv.pdf (1 page, 113367 bytes).
Transcript written on cv.log.
```