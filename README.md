# DU-Prospector
True-range multilateration implementation in LUA for Dual Universe. 

![Example](https://github.com/d6rks1lv3rz3r0/DU-Prospector/raw/main/ProspectorHUD.png)

The ultimate ore scanner triangulation script. Will help you lock onto a node on your scanner with incredible accuracy after you spend about 10 seconds taking 3 scanner measurements. You will find nodes as if you put them there. Comes with an insanely sleek HUD that makes it super easy to use. 

## Installation: 
Copy the contents of "Prospector.json", right click a programming board or remote controller -> Paste Lua Configuration from Clipboard!

## Guide: 
https://www.youtube.com/watch?v=qjgPgsh_Z0s

## Exported Variables:
- ColorTheme: hex code for color. Google HTML colors.
- SafeHUDOff: auto shut off for HUD after 3 points.
- DrawHelp: show help screen on startup.

## Testimonials:
- Stop the black magick! (Old Timey Miner)
- Never thought somebody would find a real life application area for high school math! (Raging Angsty Kid)
- You mean I haven't been mining all this time? (Soul-searching Deepthinker)

## Notes:
**Warning! -  If while having a HUD on, you press TAB or Enter to get the pointer out, and you click ANYWHERE other than the chat window (greyed out areas) it will immediately induce lag. Use Alt-1 to toggle the HUD off after you take measurements and before you click the resulting points to safely avoid this. Press Alt-1 to toggle it back on for a new measurement afterwards.**

*Scanners are slightly borked in the game at the moment in terms of  consistency of the values they return. This results in readings much more inaccurate than usual. In an effort to alleviate this, try putting a longer distance between each point scan, and walk around in the same spot a bit to stabilize the scanner.*

## References
[1] Trilateration and extension to Global Positioning System navigation, Bertrand T. Fang, Journal of Guidance, Control, and Dynamics 1986 9:6, 715-717

[2] https://en.wikipedia.org/wiki/True-range_multilateration#Three_Cartesian_dimensions,_three_measured_slant_ranges
