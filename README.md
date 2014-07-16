Nerdy Derby Race Track
======================

This instance of the Nerdy Derby Race Track is a derivative of the
Nerdy Derby project as found at http://nerdyderby.com. Their most
excellent work was an inspiration to creating this one.

As stated on the Nerdy Derby website, "The Nerdy Derby is a no-rules*
miniature car building and racing competition inspired by the Cub
Scouts' Pinewood Derby. With a larger, more undulating track and no
restrictions on the size of the cars or materials participants can
use, the Nerdy Derby rewards creativity, cleverness and ingenuity."

The work represented by these files is intended to help others create
their own tracks and may cause more harm than help. Verify, recheck
and then recheck again everything before you use these files.


Files
-----

The original design came in a reduced scale as a PDF file. The design
was re-implemented in Autodesk Inventor with _nd.iam_ being the
primary assembly file. The _nd-NUMBER.ipt_ and _nd-LETTER.ipt_
represent the individual inside and outside track segments as starting
with the finish line.

The _nd-NUMBER.dxf_ and _nd-LETTER.dxf_ files are the faces of track
segments needed by VCarve Pro to setup the tool path for a ShopBot
Alpha to cut the segments from 3/4" plywood.

The _nd-NUMBER*.crv_ and _nd-LETTER*.crv_ files are the VCarve Pro
files used to generate the _nd-NUMBER*.sbp_ and _nd-LETTER*.sbp_
ShopBot files.

The ShopBot files may or may not work for you. Ensure that you've
verified them before starting them on a ShopBot. If needed, there
should be enough detail in the other files to create the needed
ShopBot files for your installation.

The _track*.skp_ files were an early attempt to create the track
segments using SketchUp. But since Sketchup's circles and curves are
segmented lines, this effort was abandonded and Inventor was used
instead.


Build Time
----------

The curved segments for the track were cut out on a ShopBot Alpha
useing 3 pieces of 3/4" plywood. This work took approximately 8 hours
of ShopBot time.

The straight segments were cut out on a table saw using 2 pieces of
3/4" plywood along with the left over piece from the curvd
segments. This was approximately 4 hours of work.

Glue up of the segments took approximately 5 hours. First assembly
took an additional hour. Standing the track took another 2 hours.

There's another 2 or 3 hours used to buy supplies, transport
materials, etc.

The design work consumed on the order of 6 hours.


Notes
-----

  * Cutting the straight segments on a tablesaw saved ShopBot time but
    cost sanding time since the cuts were not a precise as would have
    been on the ShopBot.

  * The segments should have been numbered / lettered and a toolpath
    created to carve the numbers / letters into the segments on the
    ShopBot. By not doing this, some amount of time was used to just
    organize the segments so that the correct ones were glued
    together.

  * Don't forget to zero the z axis. The ShopBot doesn't know and will
    happily carve into your material and possibly break bits and
    parts.

  * In VCarve Pro, set up 2 tabs per piece, especially for longer pieces.

  * The default 1/8" tab is too shallow for plywood. Use 1/4" tabs.

  * Ensure that the tabs aren't being cut by a previous or following pass.

  * Make sure tabs aren't connected to other pieces that are cut out.

  * The ShopBot files were exported from VCarve Pro as Shopbot alpha w/ speed.
