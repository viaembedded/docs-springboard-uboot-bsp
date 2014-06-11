.. _display:

Display parameters
------------------

.. data:: wmt.display.param

Display settings, for example ``setenv wmt.display.param 4:6:1:1920:1080:60``. The options follow as ``type:op1:op2:resx:resy:fps``.

   :param type: Output type, acceptable values are listed below
   :param op1:  Option 1 (?)
   :param op2: Option 2 (?)
   :param resx: Horizontal number of pixels for the monitor
   :param resy: Vertical number of pixels for the monitor
   :param fps: Monitor update rate in Hz, eg. 60, or 75.

The acceptable types are:

   +---------+----------------------------------------------------------+
   | Types   | Meaning                                                  |
   +=========+==========================================================+
   | ``0``   | ``VOUT_SD_ANALOG``, ?                                    |
   +---------+----------------------------------------------------------+
   | ``1``   | ``VOUT_SD_DIGITAL``, ?                                   |
   +---------+----------------------------------------------------------+
   | ``2``   | ``VOUT_LCD``, ?                                          |
   +---------+----------------------------------------------------------+
   | ``3``   | ``VOUT_DVI``, DVI output                                 |
   +---------+----------------------------------------------------------+
   | ``4``   | ``VOUT_HDMI``, HDMI output                               |
   +---------+----------------------------------------------------------+
   | ``5``   | ``VOUT_DVO2HDMI``, ?                                     |
   +---------+----------------------------------------------------------+
   | ``6``   | ``VOUT_LVDS``, LVDS output                               |
   +---------+----------------------------------------------------------+
   | ``7``   | ``VOUT_VGA``, VGA output                                 |
   +---------+----------------------------------------------------------+
   | ``8``   | ``VOUT_BOOT``, boot time, special case for boot logos    |
   +---------+----------------------------------------------------------+
   | ``9``   | ``VOUT_MODE_MAX``, ?                                     |
   +---------+----------------------------------------------------------+
   | ``10``  | ``VOUT_MODE_ALL``, equal to ``VOUT_MODE_MAX``            |
   +---------+----------------------------------------------------------+
