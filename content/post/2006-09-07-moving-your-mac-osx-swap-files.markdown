---
categories:
- macosx
- performance
date: 2006-09-07T00:00:00Z
title: Moving Your Mac OSX Swap Files
url: /2006/09/07/moving-your-mac-osx-swap-files/
wordpress_id: 53
wordpress_url: http://tragicallyleet.com/2006/09/07/moving-your-mac-osx-swap-files/
---

When I installed my copy of Tiger I set up a 2GB partition for my swap files.  I have not used it until today and man are things faster!

The problem is that when your swap files (which are created and destroyed as needed) are on the same partition as your data, the system slows down.  The reason is that as you use the drive, the files become fragmented meaning you spend more time looking for all the pieces.  By moving to a separate partition (a separate drive would be better, but I am working on a laptop) that is not used for anything else the fragmentation is limited.

Check out the procedure [here.](http://www.bombich.com/mactips/swap.html)
