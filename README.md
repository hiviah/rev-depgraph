rev-depgraph - graphing reverse dependencies in Gentoo
====================================

WARNING: this is old as hell (2007), but I still used it up until beginning of 2012 with success.



For help, run without parameters or with --help:
rev-depgraph --help

To get help on some specific command, e.g. vicinity, run:
rev-depgraph vicinity --help

If the homepage wasn't available at the location, google for "rev-depgraph", you'll
surely find it.

REQUIREMENTS:
    * Python >= 2.4 (dev-lang/python >= 2.4)
    * gentoolkit (app-portage/gentoolkit >= 0.2.3-r1)
    * optional graphviz (media-gfx/graphviz >= 2.12 -
      actually I think >= 2.6 would be good enough, but not tested)

INSTALL
There is no install script, just copy the files somewhere in your PATH (e.g.
/usr/local/bin). The gvgen.py must be somewhere where python can find it (see
PYTHONPATH environment variable), or in the same directory as rev-depgraph.

