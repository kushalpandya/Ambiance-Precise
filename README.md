Ambiance-Precise
================

Ubuntu (12.04) Ambiance Theme fully fixed with dark context menus, dark nautilus sidebar, and fixed Panel Menu font color issues in GNOME classic session.

Purpose
-------

Starting with Ubuntu 10.04 LTS, Ubuntu got rebranded with new Light-Themes that included Ambiance (a dark theme) and Radiance (a light theme).
During the releases of Ubuntu from 10.04 through 12.04, several improvements and tweaks made to these themes.

But, Ambiance theme shipped with Ubuntu 12.04 had several issues.

* The context menus still appear light, in spite of theme being darker.
* GNOME main menu in panel in GNOME class session, had font color dark gray instead of White.
* Nautilus sidebar looks ugly with light color where toolbar, window frame are dark.

Fixes made with Ambiance-Precise
--------------------------------

The theme fixed all above mentioned UI glitches.

* Context menus are dark, to match with rest of the theme (a fix).
* Font color of panel menu in classic mode is white and icon is also visible (a fix).
* Nautilus now has dark sidebar (new addition).
  

There is a [long discussion on Launchpad][discussion] with many affected Users
which you should read if you want the full story.

  [discussion]: https://bugs.launchpad.net/ubuntu/+source/light-themes/+bug/925895

Installating the Theme
----------------------

[Download this repository][download] and extract it in `~/.themes/`. Use
`gnome-tweak-tools` or `ubuntu-tweak` to change the theme to 'Ambiance-Precise'.
Note it will not show up in the list of available themes in the 'Appearance'
settings panel.

  [download]: https://github.com/kushalpandya/Ambiance-Precise/zipball/master

Bugs/Issues
-----------

Any theme issues should be reported against the master [Light Themes][master]
project. Those related to wrong menu colouring should be reported in here.

  [master]: https://code.launchpad.net/~ubuntu-art-pkg/light-themes/trunk

Useful Links
-------------

* [Ambiance-Fixed][fixed]: Fixed Panel Menu Font Colors issue under GNOME Classic.
* [Radiance-Fixed][fixed]: The panel menu font color issue also fixed in Radiance.
* [AmbianceOneiric][fixed2]: Dark Context-menus, originally fixed by [StanAngeloff][userstanangeloff].

  [fixed]: https://code.launchpad.net/~jbicha/light-themes/fix-ambiance-in-gnome-panel/+merge/103001
  [fixed2]: https://github.com/StanAngeloff/AmbianceOneiric
  [userstanangeloff]: https://github.com/StanAngeloff
  
