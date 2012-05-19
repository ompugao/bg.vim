bg.vim
=======

Description
-----------
vim$B$N%P%C%/%0%i%&%s%I$G!"(Bgrep$B$d(Bmake$B$r<B9T$9$k$?$a$N%W%i%0%$%s$G$9!#(B
grep$B$O(B&grepprg$B$G;XDj$5$l$k30It(Bgrep$B$r;HMQ$7!"(Bmake$B$O(B&makeprg$B$G;XDj$5$l$k%3%s%Q%$%i$r;HMQ$7$^$9!#(B
vimproc$B$GHsF14|E*$K<B9T$r9T$$!"$=$N7k2L$rDj4|E*(B(au CursorHold)$B$K<hF@$7$F!"(BQuickFix$B$KDI2C$9$k$h$&$KF0:n$7$^$9!#(B
$B%P%C%/%0%i%s%I<B9TCf$O0l;~E*$K(Bupdatetime$B$rJQ99$7$^$9$,!"<B9T40N;8e$K85$KLa$7$^$9!#(B
$B$=$N$?$a!"(Bupdatetime$B$K0MB8$9$k$[$+$N%9%/%j%W%H$H6%9g$9$k2DG=@-$,$"$j$^$9!#(B
$B$^$?!"%P%C%/%0%i%s%IF0:nCf$KJL$N%P%C%/%0%i%&%s%I=hM}$r9T$&$H!"0JA0$N%P%C%/%0%i%s%IF0:n$O%-%c%s%;%k$5$l$^$9!#(B
QuickFix$B$N%&%#%s%I%&$G%+!<%=%k$,:G8e$N9T$K$"$k>l9g!"<+F/%9%/%m!<%k$7$^$9!#(B
$B%P%C%/%0%i%&%s%IF0:nCf$K(BQuickFix$B$+$i%8%c%s%W$9$k$3$H$b2DG=$G$9!#(B

Requirements
------------
$B$3$N%9%/%j%W%H$O!"(Bvimproc$B$rI,MW$H$7$^$9!#(B
vimproc$B$r%$%s%9%H!<%k$7$F$/$@$5$$!#(B

Usage
-----

### grep ###
    :Background grep [grep-args]

### make ###
    :Background make [grep-args]

### cancel ###
    :Background cancel


HISTORY
-------

### v0.2.0 by yuratomo ###
* Support make.
* Change command name. (BG to Background)

### v0.1.0 by yuratomo ###
* first version.
