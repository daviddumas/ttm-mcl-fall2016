Tangle Toy Moduli
=================

This is the code repository for an undergraduate research project of the
[Mathematical Computing Laboratory](http://mcl.math.uic.edu/)
at
[UIC](http://uic.edu/)
that was conducted in Fall 2016.

The purpose of this project was to create a WebGL visualization tool
for exploring the spaces of configurations (or *moduli spaces*) of
mechanical linkages constsing of quarter-circular struts connected by
rotating joints.  (Linkages of this type, sometimes called "tangle toys",
are often sold as desk toys.)

This project was inspired by a description of the 8-link moduli space
developed by Kasra Rafi and Gemma Zhang.

Using the simulator
-------------------

The main window shows a 3d rendering of the linkage.  A GUI panel in
the upper right allows the angles of the joints to be changed using
sliders.  Some special configurations can be selected from the
drop-down menu.

Click and drag in the main window to rotate the view.  Mouse scroll
evens zoom in or out.  The "H" key toggles visibility of the controls.

Known issues/limitations
------------------------

* Control panel shows sliders for joints that may or may not be
  present in the scene (depending on current number of links)

* Rotation is centered on the first link, rather than on the centroid
  of the entire linkage
  

Next steps
----------
This project ended on December 2, 2016.  Planned features that were
not added during the semester include:

* Ability to select a joint and adjust its angle with the mouse

* Support for touch events (swipe to rotate main window)

* Support for changing one angle by user input, adjusting others to
  keep the linkage closed


Development Team
----------------

Student researchers:

* Sarah Ather
* Rolando Medellin

Faculty mentors:

* David Dumas <david@dumas.io>
