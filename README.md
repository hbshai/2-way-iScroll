2-way iscroll
=============

Tweaked version of [2-way-iscroll](https://github.com/cubiq/2-way-iScroll).

 - Added 100% width/height setup
 - Fixed animation halting if user scrolls while changing pages (cannot scroll during page change)
 - Fixed y-scrolling reset error (page wasn't properly reset if user scrolled some X then some Y)

Probably introduced some bugs. Planned updates:

 - Tweak animation fix; currently a little too long, forces user to sometimes re-swipe
 - Tweak y-scroll fix; somehow needs to update x movement, looks fugly while doing y-swipes
