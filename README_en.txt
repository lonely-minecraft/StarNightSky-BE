StarNightSky BE - Read Me
=========================

A resource pack for Minecraft Bedrock Edition that shows a real star sky at night.
The sky, with constellation lines and names, slowly turns with time.

Author: lonely-minecraft.blogspot.com
        https://lonely-minecraft.blogspot.com/
Version: 1.0.0

NOT AN OFFICIAL MINECRAFT PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT.


Tested on
---------
- Tested on Windows, version v26.52.
- Not tested on other devices (phones, Switch, consoles) or other versions.
- Not tested in multiplayer.


How to install (Windows)
------------------------
1. Close Minecraft.
   (If Minecraft is open, the pack may not be imported.)
2. Double-click StarNightSky_BE.mcpack. Minecraft starts and shows that the import finished.
3. Open your world's settings and turn on StarNightSky BE under "Resource Packs".
4. Enter the world and wait for the night.
   Press F5 to switch to third person view to see the sky.

If double-clicking does not import the pack, you can install it by hand:
1. Rename StarNightSky_BE.mcpack so that it ends with .zip, and extract it.
2. Put the extracted folder (the one with manifest.json in it) into this folder.
   Press the Windows key + R, paste the line below and press Enter to open it.
   %appdata%\Minecraft Bedrock\Users\Shared\games\com.mojang\resource_packs
3. Start Minecraft.


Pack settings
-------------
In your world's settings, open "Resource Packs" and press the gear button of StarNightSky BE.

- Sky
    Choose one of five skies. The default is "Stars + lines + names".
    - Stars only
    - Stars + constellation lines
    - Stars + lines + names (in Japanese)
    - Stars + lines + names + art
    - Real sky with the Milky Way (NASA)

- Constellation lines
    For "Stars + constellation lines" and "Stars + lines + names". The default is "Standard".
    - Standard: lines based on the constellation charts on the website of the
      International Astronomical Union (IAU). (The IAU officially defines only the
      constellation boundaries; there are no official constellation lines.)
    - H.A. Rey: lines by H.A. Rey that make each figure easier to recognize.
      Some figures (Ursa Major, Pegasus and others) face another way than the standard ones.
    The art is shown with the standard lines only (it is drawn the traditional way).
    With H.A. Rey selected, "Stars + lines + names + art" shows "Stars + lines + names"
    with Rey's lines, without the art.

- Render distance (chunks)
    Set the same value as "Render Distance" in Settings > Video. The default is 16.
    If it does not match:
    - Too small: stars are drawn in front of distant hills and trees.
    - Too large: the sky disappears or parts of it are missing.
    Change this whenever you change the render distance in the video settings.

- Also show in first person view (default: off)
    In first person view, the sky moves with your view and is drawn in front of
    the ground and buildings. So the sky is hidden in first person by default.

- Seasons (default: on)
    The sky shifts a little every day, going through a whole year in 8 days.
    In the real sky, the constellations you see change with the seasons.

- Hide the sky when it rains (default: on)
    The sky is not shown on rainy nights, even under a roof.


About the sky
-------------
- The sky is shown only at night, from dusk (time 11500) to dawn (time 23500).
- It turns once a day, in the same direction as the sun and the moon.
- The Minecraft sun rises due east and passes straight overhead, so the pack shows
  the sky as seen from the equator. The North Star sits on the northern horizon.
- The sun and the moon are the ones from Minecraft. They do not move among the
  constellations like the real sun and moon.
- The original (made-up) stars of Minecraft are still visible. This pack cannot
  remove them.


Troubleshooting
---------------
- I cannot see the sky
    - Make sure it is night and you are in third person view.
    - Make sure it is not raining.
    - Make sure "Render distance" in the pack settings matches your video settings.

- The sky stays after I removed the pack
    Minecraft may keep showing a removed pack until it is restarted.
    Also, if you enter the world after removing the pack and before restarting,
    the pack may be turned on again. Remove it again as in "How to uninstall" below.

- Things look wrong together with another resource pack
    This pack replaces the player's client entity (player.entity.json).
    Another pack that replaces the same file may stop one of them from working.

- After a Minecraft update, the player looks or moves wrong
    This pack is built on the player definition of the version it was tested on.
    When an update changes that definition, the pack may no longer fit.
    In that case, remove this pack as in "How to uninstall" below.


How to uninstall
----------------
1. Turn off StarNightSky BE under "Resource Packs" in your world's settings.
2. Close Minecraft without entering the world.
3. Start Minecraft.

If you enter the world after removing the pack and before restarting, the pack may be
turned on again. (This happened when pressing "Play" straight from the settings screen.)


Credits and licenses
--------------------
See CREDITS.txt and LICENSE_d3-celestial.txt in the pack for details.

- Star data: Yale Bright Star Catalogue, 5th Revised Ed. (Hoffleit & Warren 1991), via CDS (catalog V/50)
- Constellation lines and names: d3-celestial, Copyright (c) 2015 Olaf Frohn, BSD 3-Clause License
- Font for the names: Noto Sans JP, SIL Open Font License 1.1
- H.A. Rey's constellation lines: Stellarium sky culture "modern_rey" by Stellarium's team,
    after H.A. Rey, "The Stars: A New Way to See Them" (1952), CC BY-SA 4.0
    https://github.com/Stellarium/stellarium/tree/master/skycultures/modern_rey
    Line star positions: Hipparcos Catalogue (ESA 1997)
    The textures with these lines (textures/night_sky/lines_rey.png and names_rey.png)
    are distributed under CC BY-SA 4.0. https://creativecommons.org/licenses/by-sa/4.0/
- Constellation art: Sidney Hall, "Urania's Mirror" (London, 1824), public domain.
    Scans from Wikimedia Commons, many restored by Adam Cuerden from cards owned by John Dolby.
    https://commons.wikimedia.org/wiki/Category:Urania%27s_Mirror
    The cards were fitted to the sky by their stars, clipped to the constellation
    boundaries, and the paper was turned black.
- Milky Way sky: NASA/Goddard Space Flight Center Scientific Visualization Studio;
    Gaia DR2: ESA/Gaia/DPAC. https://svs.gsfc.nasa.gov/4851


Version history
---------------
1.0.0  First release
