# station-console
A station console, to connect an operator, logger, and radio together.

# v1.0
See the `v1-eagle` branch for my first pass at this project from 2015, but note that it
is broken.  I did it in Eagle, but I've switched to KiCAD since then so I'll be starting
over for v2.

# v2.0
Working on the next version in the `master` branch.  Nearly the same architecture, but
simplifying it a bit (removing VU meters) and fixing a few things I've learned from other
projects (eg: speaker level is too much for cheap audio transformers, so drop the voltage
to line level BEFORE the transformer).

73 de KR6ZY, 2019-11-27
-Mark
