A LaTeX Dependency File Generator
=================================

This is a tiny script to extract dependency information from one or more LaTeX
files for use with GNU make.  It will automatically crawl files that are
related by `include`s.

Extracted dependencies are:

  * other LaTeX source files (`include`),
  * graphics (`import`) and
  * arbitrary source files (`lstinputlisting`).

Further dependency types will be added as soon as I need them.

