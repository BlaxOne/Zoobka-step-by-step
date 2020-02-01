Here's the steps to do the zoobka titled "Fun among the stars" (which is in 16:9 format and can be used as wallpaper).
It is a complement to the Zoobka tutorial:
https://www.gimp-forum.net/Thread-Zoobka-A-technique-to-make-beautiful-material-effects
It took me 6 minutes to complete.

In GIMP:
File>Open... "Fun_among_the_stars-step1.jpg".
File>Open as Layers... "Fun_among_the_stars-plasma.jpg" (1). Set to "Vivid light" mode.
New layer from visible. Set to "Screen" mode.
Filters>Blur>Zoom Motion Blur...: import (2) "zoom_blur1.txt".
New layer from visible
Filters>Distorts>Whirl and Pinch...: import "whirl_and_pinch.txt".
Filters>Distorts>Kaleidoscope...: import "kaleidoscope1.txt".
Duplicate. Set to "Screen" mode.
Zoom Motion Blur: import "zoom_blur2.txt".
File>Open as Layers... "A_smile_from_the_heart.jpg". Set to "Overlay" mode. Opacity 90.
New layer from visible.
Kaleidoscope: import "kaleidoscope2.txt".

(1) Or add a new layer and select Filters>G'MIC-Qt...>Rendering>Plasma for a random color scheme.
(2) To import a preset file to a filter: click on the arrow icon at the top right of the filter panel. In the menu that appears, select: "Import Current Settings from File..."
