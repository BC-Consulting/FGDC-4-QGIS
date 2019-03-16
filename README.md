<!-- Symbol 733 -->
[Symbol_733]: /img/fgdc01.jpg

# FGDC-4-QGIS

This is yet another<sup>([1][r1], [2][r2], [3][r3], [4][r4], [5][r5])</sup> FGDC fill symbols library for QGIS 3.x. All symbols tile seamlessly and most are standardised in a 50x50 pixels area. The colour of all symbols can be changed in QGIS as is the stroke width of many symbols.

The original symbols were taken from the FGDC Geologic Patterns for the Web <sup>([2][r2])</sup> and converted to QGIS parametrised svg <sup>([6][r6])</sup> in order to allow for colour changes.

## Install

The library is presented as a FGDC folder that should be placed into a SVG path in QGIS and a bunch of xml files that can be imported into QGIS Symbology.

Unzip the downloaded GitHub repo into a convenient location on your computer.

Copy the FGDC folder into a location accessible from QGIS SVG paths: *Settings -> Options -> System -> SVG paths*

Open QGIS Style manager and import the symbols in the xml files: *Settings -> Style Manager... -> Import/Export -> Import Item(s)...*

If you do not change QGIS default, you will end up with 7 new "Tags": 100-Suficial, 200-Sedimentary, 300-Igneous, 400-Misc-Metamorphic, 500-Glacial-Periglacial, 600-LithoSed and 700-LithoMetaIgneousVein.

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

Sets 100, 200, 300, 400 and 500 are for maps compositions
while sets 600 and 700 are for sections and logs compositions.

## Comments

* Colour of all symbols can be changed through the "Stroke colour" in QGIS Symbology pane.
* The two colours of symbol 426 can be changed with "Stroke colour" and "Fill colour" in QGIS Symbology pane.
* Symbol 733 can be further customised with "Fill colour" as demonstrated below:<br />
    ![][Symbol_733]  
    <br />Stroke colour: #000; (black)<br />
    Fill colour: #FFF; (red)
* Stroke width of the following symbols can also be adjusted in QGIS Symbology pane:<br />
    101, 102, 103, 123, 201, 202, 204, 214, 215, 216, 217, 218,219, 226, 228, 229, 230, 231, 232, all 300's, 401, 405, 406, 411, 416, 417, 418, 420, 423, 424, 430, 431, 432, 594, 601-624, 626-657, 659-680, 682-686, 701, 704-716, 719-733. 
* Most symbols are standardised on a 50x50 pixels area,<br />
    Exceptiona are all 600's symbols and symbols: 304, 411, 427, 428, 434, 435, 436, 592 and 593.
* The library does not include some of the original FGDC symbols because they can be replicated with others using QGIS options (i.e. "Texture width" and "Stroke width").

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

Last updated: 16 March 2019
