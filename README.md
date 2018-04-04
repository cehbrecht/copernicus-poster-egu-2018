# Copernicus CP4CDS Poster for EGU 2018

Copernicus WPS Poster for [EGU 2018](https://www.egu2018.eu/) in Vienna.

This poster is generated with LaTeX.

## Using Git Large File Storage

This Git repository is using the Git Large File Storage extension for versioning large files.

See the [documentation](https://git-lfs.github.com/) on how to install this extension and enable it.


## Build PDF

Use the ``Makefile`` and just type:

    $ make

Or:

    $ pdflatex --enable-write18 copernicus-poster-egu-2018.tex

## Draw.io Diagrams

Diagrams are created using [draw.io](https://www.draw.io/):

* [CP4CDS](https://www.draw.io/#Hcehbrecht%2Fcopernicus-poster-egu-2018%2Fmaster%2Fdraw.io%2Fcp4cds.xml)

Diagrams (and exported PNG files) are in the folder ``draw.io/``.


## Requirements

* You need a LaTeX installation, for example [MikTeX](https://miktex.org/)
* Poster is using the [baposter](http://www.brian-amberg.de/uni/poster/) LaTeX template. It is already part of the sources.
