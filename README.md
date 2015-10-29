RPI Thesis LaTeX
================

Check out the original version [markemer/rpi-latex-thesis](http://github.com/markemer/rpi-latex-thesis).

I have made a number of changes to the Thesis class;
**These changes are in no way endorsed by any official at RPI/OGE.**


## Summary of Changes

- Now using Unix line-endings, with no blank spaces at the end of lines
- Commented out the bibentry def.
  Un-comment [line 314](https://github.com/gonsie/rpi-latex-thesis/blob/master/thesis.cls#L314) "for use in making an unnumbered bibliography with hanging indents."
- Added a Candidacy title page (no signature lines).
  Use the command `\softtitlepage`.
- Added command for self attribution footnote. See [template/rpithes.tex:27](https://github.com/gonsie/rpi-latex-thesis/blob/master/template/rpithes.tex#L27) and the OGE Thesis Manual (page 12).
