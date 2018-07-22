## Transporter for technic
This mod adds a technic-powered, highly configurable transporter.  

#### Depends

* default
* technic

#### Usage
* Simply connect the transporter to a technic power network.  

* Right-clicking it brings a transporter menu, where you can set the target coordinates 
(don't forget to click set to actually set the coordinates), bookmarks menu and other 
settings.  

* The transporter establishes a portal between two points, teleporting any players and remaining
active as long as enough energy is supplied.  

* The transport cost is calculated based on distance between the points multiplied by per-node modifier (20 by default)
and two-way modifier (if the portal is two-way, twice as much energy is used).  

* One-way checkbox enables the transporter to automatically shutdown after one teleportation (from any side).  

* You can save bookmarks from a transporter node by right-clicking it with a blank floppy disk. It will become blue and right-clicking
any transporter node will add bookmarks stored on this floppy to the transporter.  

#### License

* Code is LGPL v3.
* Resources (all textures and sounds) are CC-BY-SA 3.0.

#### Sound project note

Although I included an ardour project, to actually open it you'll need at least ardour 5.12 as well as lv2 plugins: 
calf suite (calf) and helm synthesizer (helm) installed and registered within ardour. On arch linux all of these 
are available from the official repositories.

