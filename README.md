# magic-wand
<a href="https://eigenlucy.github.io/projects/magic-wand">Battery pack for wireless Hitachi Magic Wand operation.</a>

# Features
<li>3A USB-C rapid charging</li>
<li> [Capacity] mAh battery provides [hours] of  use</li>
<li>Plugs directly into the back of a Hitachi Wand/Hitachi Wand Plus</li>

# Dependencies
<li><a href="https://docs.atopile.io/latest/">atopile</a></li>
<li><a href="https://www.kicad.org/">KiCAD</a></li>

# Directory
<li>elec/src/ contains the atopile code which wires PCBs, generates netlists, generates BOMs, etc</li>
<li>elec/layout contains a kicad project for each build, which can be used to edit PCB layouts. Default is the final PCB containing all subbuilds</li>
<li>mech will contain CAD assembly files and STLs</li>
<li>Gerbers and other PCBA files can be accessed through the Actions run completed on each commit. Build artifacts contain everything necessicary to order assembled PCBs for JLCPCB</li>
