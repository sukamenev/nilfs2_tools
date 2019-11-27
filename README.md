# n2u - utils for show history of file

This script return history of file item on NILFS2 filesystem.

Copy script to /usr/local/bin.

*USAGE*: n2u log [--revision|-cp|-r cp1:cp2|{YEAR-MM-DD}:{YEAR-MM-DD}] filename.

*USAGE*: n2u blame [--revision|-cp|-r cp1:cp2|{YEAR-MM-DD}:{YEAR-MM-DD}] filename.

*USAGE*: n2u diff --revision|-cp|-r cp1:cp2  filename.

*NOTE*: You need root privilegies and installed nilfs2 utilities.
