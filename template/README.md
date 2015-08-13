# RPI Thesis Template

These template files were originally downloaded [here](http://dotcio.rpi.edu/services/printing-publishing/thesis-preparation).

## Origanization

If your thesis is short, you may want to keep all the sorce code within one file.
In this case, see the `rpithes-short.tex` template file.

As is more likely the case, your thesis will be significantly complex and you will want break the source into multiple files.
The provided template files are divided in the following way:
- `rpithes.tex`: this is root/top-level file.
  The document class is set here.
  Any packages (or other preamble definitions) are added here.
  All sub-files are linked with an `\include{}` command, within the `\begin{document}` and `\end{document}` commands.
  - `rpititle-phd.tex` or `rpititle-mas.tex`: title page
  - `rpiack.tex`: acknowledgements page
  - `rpiabs.tex`: abstract page
  - `rpichap1.tex` and `rpichap2.tex`: chapters of the thesis
  - `rpibib.tex`: bibliography page
    Note that this **IS NOT** the recommended way to create a bibliography.
    It is recommended that you use additional software, such as BibTeX, Zotero, or EndNote.
  - `rpiapp.tex`: appendix page
