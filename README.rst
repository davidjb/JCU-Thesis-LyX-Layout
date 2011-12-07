About this layout
=================

This is a layout for theses written at `James Cook University (JCU)
<http://www.jcu.edu.au>`_ for the very the fantastic `LyX
<http://www.lyx.org/>`_ document processor.  

This layout automagically inserts the required details into your thesis
(Honours or PhD), assuming that you give the correct details to LyX. 

In case you're unaware, LyX is a WYSIWYM (what-you-see-is-what-you-mean) editor
for LaTeX, which makes great looking documents. LyX is free, it's more powerful
and simpler to produce your document than Word, and if you're not using it, you
should be because you just found about it.

Contributing
============

Please feel free to fork this repository as required on GitHub and contribute
fixes as pulls. If you are going to be active in development, you can be added
to this project; please send contact for details and you too can commit code!

Attribution/Evangelism
======================

I'd appreciate you acknowledging work on this layout in your thesis. Hopefully
one day JCU students will help each other by working on this layout into the
future.

Even if you don't acknowledge your use of this layout, hopefully you can see
the benefit of telling your fellow students, staff, researchers etc (even
cross-discipline!) about this. Help them set this up too!

Usage
=====

Clone this GitHub repository to your local computer (using *Git*, of course).
You need to place the files here either within your `~/.lyx` directory, or if
you prefer, directly next to your pre-existing LyX document in the same folder.

Tell LyX to use that layout. See LyX's `Document` menu, and click onto
`Settings`.  Locate the `Document Class` entry and select this layout.  If
you've placed the layout next to your document, then choose `Local Layout` and
browse for the layout. LyX might warn you here, but just make sure all the
unzipped files are in the same folder as your original document itself.

Now, generally near the start of the document, use the available section styles
(also slightly confusingly called "Layouts") within LyX to create a:

* `Title`
* `Author`, with your name
* `Degree`, with something like *Bachelor Of Information Technology with
  Honours*
* `School`, with something like *Information Technology*
* `University`, with *James Cook University*
* `Crest Filename` with the local file name of a JCU logo you have. This
  repository comes with `jculogo.pdf`, a vectorised version of the new-style
  JCU logo. The repository also comes with an SVG version of this logo, which
  you can use to render out a specific size logo if required. If you've got a
  specific JCU school picture or logo, then you can use something else.

Optional custom sections
------------------------

You'll probably want these, but they are optional. Add them by selecting them
from the layouts drop-down menu:
    
* Acknowledgements
* Abstract

You should add these immediately after your front page configuration to improve
the logical structure of your LyX document.

Standard sections
-----------------

Beyond this, you can add everything else like Table of Contents, Figures,
Bibliography and more, and the rest of your document. Use the relevant
`Section` styles/layouts to partition your document accordingly.

LaTeX Preamble
--------------

When you start your document, insert this code: ``\pagenumbering{arabic}``
either as ERT (Evil Red Text; TeX Code: ``Ctrl+L``) or as LaTeX Preample (under
`Settings`) to start the document numbering correctly.

Go!
---

That's it! Render the document as PDF using LyX and see what happens. If you
find errors, it's because you're missing some LaTeX packages. Configure your
typeset program (MikTeX if you're on Windows) to automatically download missing
packages, then run ``Reconfigure`` on LyX, restart it, and go again. Make sure
you're on the Internet first before you do this as new packages need a network
connection in order to be downloaded!

The layout and class here can be modified to suit your needs, if they're
different, without too much effort, so keep that in mind!

Origins
=======

The layout was originally designed as part of a 2008 Honours thesis and has
been used by a variety of students since. The wording and specifics of some
parts of the document, such as the Abstract, are specifically taken from the
2008 guidebook for Honours in Information Technology.  As such, the wording
may change (or have changed since then) or possibly be different for your
discipline.  
