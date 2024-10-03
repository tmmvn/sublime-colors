# 🎨 Gutter Color for Sublime Text 4
This plugin provides gutter colors whenever there's color codes on the code
lines. I ended up going further up the fork tree since I had some whack behavior
with the repo I forked this from.

In addition to going further up the fork tree, I removed all color highlighting
from the plugin. Due to syntax coloring, I only want extra colors to show up in
the gutter.

I might structure the code better at some point and see if there are any
optimizations that could be done. One key change I did was to use the Sublime
cache directory instead of the user package directory for the icon caches. I
also added automatic cleaning of the cache (time-based) to prevent the cache
from growing forever (or more like until all possible colors have been seen).

## License
Changes by Tommi Venemies, 2024.
Copyright (C) 2018 German Mendez Bravo (Kronuz). All rights reserved.

MIT license

This plugin was initially a fork of
https://github.com/Monnoroch/ColorHighlighter
