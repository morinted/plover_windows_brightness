Plover Windows Brightness Control
=================================

Add support for controlling Windows monitor brightness from Plover.

Sample Usage
------------

Monitor brightness is a value between 0 and 100. You have three
available commands to manipulate this brightness: BRIGHTNESS_SET, BRIGHTNESS_UP, and BRIGHTNESS_DOWN.

Increase Brightness
~~~~~~~~~~~~~~~~~~~

-  ``{PLOVER:BRIGHTNESS_UP}``

   Increase brightness by 10 points.
-  ``{PLOVER:BRIGHTNESS_UP:20}``

   Increase brightness, specifying 20 points.

Decrease Brightness
~~~~~~~~~~~~~~~~~~~

-  ``{PLOVER:BRIGHTNESS_DOWN}``

   Decrease brightness by 10 points.
-  ``{PLOVER:BRIGHTNESS_DOWN:20}``

   Decrease brightness, specifying 20 points.

Setting Brightness
~~~~~~~~~~~~~~~~~~

-  ``{PLOVER:BRIGHTNESS_SET:50}``

   Set brightness to half.