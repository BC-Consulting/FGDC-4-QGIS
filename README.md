# FGDC-4-QGIS

This is yet another<sup>([1][r1], [2][r2], [3][r3], [4][r4], [5][r5])</sup> FGDC fill geology symbols library for QGIS 3.x. All fill symbols tile seamlessly and most are standardised in a 50x50 pixels area. The colour of all symbols can be changed in QGIS as is the stroke width of many symbols.

The original symbols were taken from the FGDC Geologic Patterns for the Web <sup>([2][r2])</sup> and converted to QGIS parametrised svg <sup>([6][r6])</sup> in order to allow for colour changes.

## Install

The library is presented as a FGDC folder that should be placed into a SVG path in QGIS and a bunch of xml files that can be imported into QGIS Symbology.

Download this repo to your computer.

Unzip the downloaded GitHub repo into a convenient location on your computer.

Copy the FGDC folder (not collections/FGDC) into a location accessible from QGIS SVG paths: *Settings -> Options -> System -> SVG paths*

Open QGIS Style manager and import symbols from each xml file: *Settings -> Style Manager... -> Import/Export -> Import Item(s)...*

If you do not change QGIS default, you will end up with 7 new "Tags": 100-Suficial, 200-Sedimentary, 300-Igneous, 400-Misc-Metamorphic, 500-Glacial-Periglacial, 600-LithoSed and 700-LithoMetaIgneousVein.

Each tag will have the following number of symbols in it: 


<table>
<tr>
  <td>Symbol tab</td>
  <td>&nbsp;&nbsp;</td>
  <td>Nb. symbols</td>
 </tr>
 <tr>
  <td align="right">100-Suficial</td>
  <td align="center"></td>
  <td align="center">21</td>
 </tr>
 <tr>
  <td align="right">200-Sedimentary</td>
  <td align="center"></td>
  <td align="center">18</td>
 </tr>
 <tr>
  <td align="right">300-Igneous</td>
  <td align="center"></td>
  <td align="center">14</td>
 </tr>
 <tr>
  <td align="right">400-Misc-Metamorphic</td>
  <td align="center"></td>
  <td align="center">26</td>
 </tr>
 <tr>
  <td align="right">500-Glacial-Periglacial</td>
  <td align="center"></td>
  <td align="center">9</td>
 </tr>
 <tr>
  <td align="right">600-LithoSed</td>
  <td align="center"></td>
  <td align="center">84</td>
 </tr>
 <tr>
  <td align="right">700-LithoMetaIgneousVein.</td>
  <td align="center"></td>
  <td align="center">32</td>
 </tr>
</table>

Symbol sets 100, 200, 300, 400 and 500 are for maps compositions while sets 600 and 700 are for sections and logs compositions.

More information and lists of symbols available in the library can be found [here](http://www.geoproc.com/tut/qgis-fgdc.php), on GeoProc.com web site.

**Alternatively**, you can use the ["Resources Sharing"](http://www.akbargumbira.com/qgis_resources_sharing/) plugin to add this collection:\
Settings -> Add repository...:\
--- Name: FGDC Geology Symbols\
--- URL: https://github.com/BC-Consulting/FGDC-4-QGIS.git

## Licence

![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)
All the symbols in this library are distributed under [CC0](http://creativecommons.org/publicdomain/zero/1.0/).
To the extent possible under law GeoProc.com, formerly BC-Consulting, has waived all copyright and related or neighboring rights to this work.

## References

1. U.S. Geological Survey, 2006, FGDC Digital Cartographic Standard for Geologic Map Symbolization (PostScript Implementation): U.S. Geological Survey Techniques and Methods 11-A2 ([online](http://pubs.usgs.gov/tm/2006/11A02/))
2. Daven Quinn, 2017, FGDC Geologic Patterns for the Web ([online](https://davenquinn.com/projects/geologic-patterns/))
3. Stefan Revets, 2016, QGIS Geology Symbology ([online](https://sourceforge.net/projects/qgisgeologysymbology/))
4. Andrea Nass, Alessandro Frigeri, 2016, Geologic Symbols for digital maps and GIS ([online](https://github.com/afrigeri/geologic-symbols))
5. cecgeology, 2018, USGS-FGDC-for-QGIS ([online](https://github.com/cecgeology/USGS-FGDC))
6. How to create svg symbols that have modifiable fill color, stroke color and stroke width? ([online](https://gis.stackexchange.com/questions/45180/how-to-create-svg-symbols-that-have-modifiable-fill-color-stroke-color-and-stro))


[r1]: http://pubs.usgs.gov/tm/2006/11A02/ "1 - U.S. Geological Survey, 2006, FGDC Digital Cartographic Standard for Geologic Map Symbolization (PostScript Implementation): U.S. Geological Survey Techniques and Methods 11-A2."

[r2]: https://davenquinn.com/projects/geologic-patterns/ "2 - Daven Quinn, 2017, FGDC Geologic Patterns for the Web."

[r3]: https://sourceforge.net/projects/qgisgeologysymbology/ "3 - Stefan Revets, 2016, QGIS Geology Symbology."

[r4]: https://github.com/afrigeri/geologic-symbols "4 - Andrea Nass, Alessandro Frigeri, 2016, Geologic Symbols for digital maps and GIS."

[r5]: https://github.com/cecgeology/USGS-FGDC "5 - cecgeology, 2018, USGS-FGDC-for-QGIS."

[r6]: https://gis.stackexchange.com/questions/45180/how-to-create-svg-symbols-that-have-modifiable-fill-color-stroke-color-and-stro "6 - How to create svg symbols that have modifiable fill color, stroke color and stroke width?"

---

Last updated: 13 January 2022
