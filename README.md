    The ledmac package is for typesetting critical editions. It is a
LaTeX port, and extension, of the plain TeX EDMAC, TABMAC and EDSTANZA
macros. The ledpar package is an extension of ledmac enabling parallel
typesetting in columns or on facing pages. The ledarab package is
an extension enabling the use of arabic script, as implemented by ArabTeX, 
in critical editions (temporarily ledafoot.sty is provided to support regular 
footnotes in ArabTeX).

These 3 packages are deprecated :
	- Ledmac is replaced by eledmac, or better reledmac
	- Ledpar is replaced by eledpar, or better reledpar
	- Learab is unmaintened. You should consider using of XeLaTeX instead.

    Bug reports and suggestions are welcome.

This version of the package is stored in github
https://github.com/LaTeX-Package-Repositories/ledmac

Please use ledmac "issues"
https://github.com/LaTeX-Package-Repositories/ledmac/issues

URL in the CTAN : http://www.ctan.org/pkg/ledmac

You can subscribe to ledmac list in https://lists.berlios.de/pipermail/ledmac-users/
-------------------------------------------------------------------- 
  Author: Peter Wilson (Herries Press) herries dot press at earthlink dot net, Maïeul Rouquette (new maintainer june 2011-2015)
  Copyright 2003 --- 2005 Peter R. Wilson
  Copyright 2011 --- .. Maïeul Rouquette
  Copyright 2024 --- David Carlisle (LaTeX-Package-Repositories)
 
  This work may be distributed and/or modified under the
  conditions of the LaTeX Project Public License, either
  version 1.3 of this license or (at your option) any 
  later version.
  The latest version of the license is in
     http://www.latex-project.org/lppl.txt
  and version 1.3 or later is part of all distributions of
  LaTeX version 2003/06/01 or later.
 
  This work has the LPPL maintenance status "unmaintned".
 
  This work consists of the files:
   README (this file), 
   ledmac.dtx, 
   ledmac.ins,
   ledmac.pdf   (200+ pages)
   ledeasy.eps, 
   ledfeat.eps, 
   ledioc.eps, 
   ledarden.eps, 
   ledmixed.eps,
   ledekker.eps, 
   ledbraonain.eps,
   ledpar.dtx,
   ledpar.ins,
   ledpar.pdf   (100+ pages)
   djd17novL.eps,
   djd17novR.eps,
   djdpoems1.eps,
   djdpoems2.eps,
   djdpoems3.eps,
   djdpoems4.eps,
   villon.eps,
   ledarab.dtx,
   ledarab.ins,
   ledarab.pdf (20- pages)
   egarab.eps
   egarabpar.eps
and the derived files 
   ledmac.sty, 
   ledeasy.tex, 
   ledfeat.tex, 
   ledioc.tex, 
   ledarden.tex,
   ledmixed.tex,
   ledekker.tex, 
   ledbraonain.tex,
   ledpar.sty,
   djd17nov.tex,
   djdpoems.tex, 
   villon.tex,
   ledarab.sty
   egarab.tex
   egarabpar.tex
   ledafoot.sty

-------------------------------------------------------------------- 

    The distribution consists of the following files:
README (this file)
ledmac.dtx
ledmac.ins
ledmac.pdf
ledeasy.eps
ledfeat.eps
ledioc.eps
ledarden.eps
ledmixed.eps
ledekker.eps
ledbraonain.eps
ledpar.dtx
ledpar.ins
ledpar.pdf
djd17novL.eps
djd17novR.eps
djdpoems1.eps
djdpoems2.eps
djdpoems3.eps
djdpoems4.eps
villon.eps
ledarab.dtx
ledarab.ins
ledarab.pdf
egarab.eps
egarabpar.eps
(possibly ledpatch.sty)
(possibly ledparpatch.sty)
(possibly ledarabpatch.sty)
makefile


    To install the ledmac package:
o run: latex ledmac.ins (which will generate ledmac.sty)
o Move ledmac.sty (and ledpatch.sty if it exists) to a location where 
  LaTeX will find it (for more information on this see the FAQ).

    To generate a second copy of the manual (which is already supplied as a PDF file):
o run: make ledmac.pdf

    The *.eps files are example pages processed with the ledmac package.
They are included as figures in ledmac.dtx, which also contains the
source code for them.

    Installation of the other packages (via ledpar.ins and ledarab.ins)
is similar.
 
2012/06/07
Maïeul Rouquette
maieul at maieul dot net

2024/10/09
David Carlisle https://github.com/LaTeX-Package-Repositories/ledmac