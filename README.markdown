# Re:load #

Re:load is an adjustable dummy load with the following features:

 * No external power supply required - powered by the device under test.
 * Wide range of input voltages, from 3.3 to 30 volts.
 * Adjustable load from 0 to 3.5 amps (or 0 to 10 amps in the high current version)
 * Up to 14 watts power dissipation (40 watts in the high current version)
 * Virtually indestructible: The power FET, BTS117, has built in overtemp, ESD, and overcurrent protection. A diode protects the opamp from reverse bias.
 * Load remains constant under the whole range of input voltage.
 * Screw terminal and banana plug footprints.
 * Low BoM cost, and easy to solder thru-hole parts.
 * Test points for reading current with a voltmeter.


# BoM #

<table>
  <tr>
	<th>Name</th>
	<th>Description</th>
	<th>Part Number</th>
	<th>Quantity</th>
  </tr>
  <tr>
	<td>D1</td>
	<td>400mV dropout schottky diode</td>
	<td><a href="http://uk.farnell.com/multicomp/bat42/diode-schottky-do-35/dp/1621827">BAT42</a></td>
	<td>1</td>
  </tr>
  <tr>
	<td>C1</td>
	<td>0.1uF Ceramic Capacitor</td>
	<td><a href="http://uk.farnell.com/multicomp/mc0805104m500a2-54mm/capacitor-0-1uf-50v5v-rad/dp/2112751">MC0805Y104M500A2.54MM</a></td>
	<td>1</td>
  </tr>
  <tr>
	<td>C2</td>
	<td>10uF Aluminium Electroltyic Capacitor</td>
	<td><a href="http://uk.farnell.com/multicomp/mcrh25v106m5x11/capacitor-10uf-25v/dp/1902913">MCRH25V106M5X11</a></td>
	<td>1</td>
  </tr>
  <tr>
	<td>C3</td>
	<td>1uF Ceramic Capacitor</td>
	<td><a href="http://uk.farnell.com/multicomp/mcmlr50v105kx7r/capacitor-1uf-50v-x7r-radial/dp/2112947">MCMLR50V105KX7R</a></td>
	<td>1</td>
  </tr>
  <tr>
	<td>R1</td>
	<td>0.05 ohm 1 watt resistor</td>
	<td><a href="http://uk.farnell.com/jsp/search/productdetail.jsp?sku=1108073">LVR03R0500FE70</a></td>
	<td>1</td>
  </tr>
  <tr>
	<td>R2</td>
	<td>1k 3mm smd trimpot</td>
	<td><a href="http://uk.farnell.com/bourns/tc33x-2-102e/trimmer-1k-3mm/dp/1689862RL">TC33X-2-102E</a></td>
	<td>1</td>
  </tr> 
  <tr>
	<td>R3</td>
	<td>162k 1% resistor</td>
	<td><a href="http://uk.farnell.com/vishay-bc-components/mrs25000c1623fct00/resistor-mrs25-1-162k/dp/9464760">MRS25000C1623FCT00</a></td>
	<td>1</td>
  </tr>
  <tr>
	<td>R4, R5</td>
	<td>10k 1% resistor</td>
	<td><a href="http://uk.farnell.com/welwyn/mfr3-10kfc/resistor-metal-film-10kohm-400mw/dp/1833277">MFR3-10KFC</a></td>
	<td>2</td>
  </tr>
  <tr>
	<td>R6</td>
	<td>10k potentiometer</td>
	<td><a href="http://uk.farnell.com/alps/rk09k1130c79/potentiometer-10kb/dp/1191741">RK09K1130C79</a></td>
	<td>1</td>
  </tr>
  <tr>
	<td>IC1</td>
	<td>MCP6002 Rail-to-rail Op-amp</td>
	<td><a href="http://uk.farnell.com/microchip/mcp6002-i-p/ic-op-amp-1-8v-imhz-dual-pdip8/dp/1292245">MCP6002</td>
	<td>1</td>
  </tr>
  <tr>
	<td>IC2</td>
	<td>LP2950 3v LDO</td>
	<td><a href="http://uk.farnell.com/texas-instruments/lp2950-30lp/volt-reg-micropwr-3v-sd-to92/dp/2078559">LP2950-30LP</a></td>
	<td>1</td>
  </tr>
  <tr>
	<td>Q1</td>
	<td>3.5A N-Channel Smart FET</td>
	<td><a href="http://uk.farnell.com/jsp/search/productdetail.jsp?sku=743446">BTS117</a></td>
	<td>1</td>
  </tr>
  <tr>
	<td>JP1</td>
	<td>Terminal Block</td>
	<td><a href="http://uk.farnell.com/jsp/search/productdetail.jsp?sku=1717001">CTB5202/2</a></td>
	<td>1</td>
  </tr>
  <tr>
	<td>KK1</td>
	<td>Heatsink</td>
	<td><a href="http://uk.farnell.com/jsp/search/productdetail.jsp?sku=1710636">MC33290</td>
	<td>1</td>
  </tr>
</table>
