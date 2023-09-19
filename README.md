# CD40106 VCO

Saw-core VCO based on Moritz Klein version, with additionnal wave shaping capabilities.

Saw, Square, Sine and triangle wave output.

V/Oct, PWM and FM CV inputs. 

Octave switch and pot for fine control for each octave

Extension connector to connect to the SubPower5 (Sub octave extender, soon to be released)

You'll find the schematic of this module below: 

![CD40106 VCO schematic](documentation/image/CD40106-schematic.svg)
![CD40106 VCO schematic](documentation/image/CD40106-Filtre2.svg)

Uses an SMD LM13700 because the DIP ones are not produced anymore.

Regular build, I use ceramic capacitors but you can use film/polyester.

Polyester capacitor for the saw core. 

:warning: When building modules, always do it in this order (from smallest component to highest):
- diodes
- resistors
- DIP chips
- capacitors (film/ceramic)
- Electrolytic capacitors

For the next part, always place them without soldering them on: 
- jacks, pots and switches that go thought the front panel

Once placed, put in place the front panel, then fasten all components to it. Once this is done, you can solder them. 

![3D CD40106 VCO(front)](documentation/image/MS20-VCF-3D_top.png)

![3D CD40106 VCO(back)](documentation/image/MS20-VCF-3D_bottom.png)

![3D CD40106 VCO(iso)](documentation/image/MS20-VCF-3D_top30deg.png)

[See bom globale](documentation/bom/MS20-VCF-ibom-global.html)

[See bom board jack](documentation/bom/MS20-VCF-ibom-jack.html)

[See bom board circuit](documentation/bom/MS20-VCF-ibom-circuit.html)
