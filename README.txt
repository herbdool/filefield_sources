-----------------
FileField Sources
-----------------

Description
-----------
FileField Sources is a module that enhances the generic and image upload fields
in Backdrop. Typically such fields only allow you to upload a file from your
desktop. FileField Sources makes it so that you can populate any file field
from a variety of sources, such as entering remote URLs directly, re-use
existing uploaded files, pull from a server directory, or a variety of other
possibilities.

This module built by Robots: http://www.lullabot.com
Author: Nathan Haug (quicksketch)

Installation
------------
1) Place this module directory in your modules folder (this will usually be
   "sites/all/modules/").

2) Enable the module within your Backdrop site.

3) Add or configure an existing file or image field. To configure a typical node
   field, visit Admin -> Structure -> Content types and click "manage fields"
   on a type you'd like to modify. Add a new file field or edit an existing one.

   While editing the file or image field, you'll have new options available
   under a "File sources" fieldset. You can enable the desired sources for that
   particular field.

4) Create a piece of content that uses your file file and try it out.

Support
-------
Please file bug reports in the FileField Sources issue queue on GitHub.
http://github.com/backdrop-contrib/filefield_sources/issues
