This is a plugin for MuseScore 3 to add harmonica tablature notation below the notes. It currently supports

 * the Hohner Highlander only, for both side, A highlander and D - [Reference](http://musescore.org/sites/musescore.org/files/Hohner%20Highlander%20scale.jpg)
 * Diatonic A - [Reference](http://harmopoint.com/harmonica-virtuel/) [and for overblows and overdraws](http://www.overblow.com/?menuid=26)
 * Diatonic Bb - [Reference](http://musescore.org/sites/musescore.org/files/Lee%20Oskar%20Diatonic%20Bb.jpg) [and for overblows and overdraws](http://www.overblow.com/?menuid=26)
 * Diatonic C - [Reference](http://musescore.org/sites/musescore.org/files/Lee%20Oscar%20C.jpg) [and for overblows and overdraws](http://www.overblow.com/?menuid=26)
 * Diatonic D - [Reference](http://musescore.org/sites/musescore.org/files/Lee%20Oskar%20Diatonic%20D.jpg) [and for overblows and overdraws](http://www.overblow.com/?menuid=26)
 * Diatonic F - [Reference](http://harmopoint.com/harmonica-virtuel/) [and for overblows and overdraws](http://www.overblow.com/?menuid=26)
 * Diatonic G - [Reference](http://musescore.org/sites/musescore.org/files/Lee%20Oskar%20%20Diatonic%20G.jpg) [and for overblows and overdraws](http://www.overblow.com/?menuid=26)
 * Chromatic C, 12 holes - [Reference](http://musescore.org/sites/musescore.org/files/12%20Hole%20Chromatic%20slide%20Harmonica.txt)
 * Chromatic C, 16 holes - [Reference](https://coast2coastmusic.com/chromatic/tuning_charts.shtml)


If you want to have your harmonica added to the it, please contact me, or better, do a pull request.


##Convention
* `+4`    = blow
* `-4`    = draw
* `-3b`   = halfstep bend
* `-3bb`  = whole step bend
* `-3bbb` = 3 halfsteps bend
* `+6o`   = overblow
* `-9o`   = overdraw
* `+4s`   = slide (chromatic)
* `+1*`   = lower register in 16 holes chromatic (1*, 2*, 3*, 4*, 1, 2, 3, 4, 5, 6, 7 , 8, 9 ,10, 11, 12)


Bends, over blow, over draw may be supported if it's the only way to play the note.
If there are two holes for one note, a choice has been made (draw)

##More info
See the official [project page](http://musescore.org/en/project/harmonicatablature)
