# elegoo-neptune2-cura
A quick hack around to try to reproduce the Elegoo provided Cura setup in Cura 4.13.1

All the defaults should be as close to what you get from the Elegoo Cura version as possible.  I still got some extrusion value differences when running a diff on the gcode of Elegoo vs Standard, which could just be due to changes in Cura versions.
I avoided trying to make any 'improvements' in the defaults so that this can be a base for people to work from with their own profile overrides.

Copy the 3 folders to your Cura configuration directory to add a new Elegoo Neptune 2 option when adding your printer.  This _may_ conflict with the Toylerr version if also installed in which case a full clean of the install may be required.

There is an additional improved-top-bottom.curaprofile which I used to fix some issues I was getting with gaps in the top layer, but this comes with an extra time cost.

Bed STL taken from https://github.com/Toylerrr/ELEGOO_Neptune2_Cura
