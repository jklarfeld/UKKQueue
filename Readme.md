UKKQUEUE 
–Updated for Automatic Reference Counting (ARC)
============

A wrapper class around the kqueue file change notification mechanism.

Simply create a UKKQueue (or use the singleton), add a few paths to it and listen to the change notifications via NSWorkspace's notification center.

Installation
-------------

Use cocoapods. It will make life easier.

    pod 'UKKQueue', '~> 0.5'
    $ pod install

This may require to add some additional spec repo to our pods. This can be done through

    $ pod remote add PodSpecs git@github.com:mcb/PodSpecs.git

LICENSE
-------------

(c) 2003-06 by M. Uli Kusterer. You may redistribute, modify, use in
commercial products free of charge, however distributing modified copies
requires that you clearly mark them as having been modified by you, while
maintaining the original markings and copyrights. I don't like getting bug
reports about code I wasn't involved in.

I'd also appreciate if you gave credit in your app's about screen or a similar
place. A simple "Thanks to M. Uli Kusterer" is quite sufficient.
Also, I rarely turn down any postcards, gifts, complementary copies of
applications etc.


Contact
-------------

Get the newest version at http://www.zathras.de
E-Mail me at witness (at) zathras (dot) de or witness (dot) of (dot) teachtext (at) gmx (dot) net
