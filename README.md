my_cv
=====

Project overview
----------------

It's a Latex project using TeXlipse plugin.

I have used a template to generate my curriculum vitae.

Fedora install
--------------
```yum -y install texlive texlive-bigfoot texlive-lipsum texlive-hyphenat```

Eclipse
-------
Import project into Eclipse workspace
Change perspective to Latex
Go to the project properties
On Latex Project Properties check the output format is pdf and the build command is pdflatex

PDF File compression
--------------------
If you want to compress generated pdf file you can do it by this two commands:

```pdf2ps your_cv.pdf```

```ps2pdf your_cv.ps your_cv_compressed.pdf```

Enjoy !
