---
layout: post
title:  "Measuring current"
date:   2013-09-03 00:10:00 +0000
categories: Testing
permalink: measuring-current
---

The <a title="International System of Units" href="http://en.wikipedia.org/wiki/International_System_of_Units">SI</a> unit for measuring an electric current is the <a title="Ampere" href="http://en.wikipedia.org/wiki/Ampere">ampere</a>.

To measure current the multimeter has to be inserted into the circuit. The multimeter is set to mA (milliamps).

A simple circuit is set up with a 1k resistor, a 2k pot and 4xAA batteries. I measure the current with the pot closed, halfway and open.

Potentiometer closed
![Potentiometer closed]({{ site.baseurl }}{{ post.url }}/img/2013-09-03-potentiometer-closed.jpg)

Potentiometer halfway
![Potentiometer halfway]({{ site.baseurl }}{{ post.url }}/img/2013-09-03-potentiometer-halfway.jpg)

Potentiometer open
![Potentiometer open]({{ site.baseurl }}{{ post.url }}/img/2013-09-03-potentiometer-open.jpg)

The table below shows the results
<table>
<tbody>
<tr>
<th>Resistor</th>
<th>Potentiometer</th>
<th>Total resistance</th>
<th>Current</th>
<th>Voltage</th>
</tr>
<tr>
<td>(KΩ)</td>
<td>2KΩ</td>
<td>(KΩ)</td>
<td>(mA)</td>
<td>(Volts)</td>
</tr>
<tr>
<td>0.99</td>
<td>Closed (2.01KΩ)</td>
<td>3</td>
<td>2.13</td>
<td>6.42</td>
</tr>
<tr>
<td>0.99</td>
<td>Half (1KΩ)</td>
<td>1.98</td>
<td>3.21</td>
<td>6.42</td>
</tr>
<tr>
<td>0.99</td>
<td>Open (0.02KΩ)</td>
<td>1.01</td>
<td>6.41</td>
<td>6.42</td>
</tr>
</tbody>
</table>

<br>

If we multiply the resistance by the amperage, we (roughly) end up with the voltage each time.
<p style="padding-left: 30px;"><em>voltage = kilohms x milliamps</em></p>
1K is 1,000 ohms, and 1mA is 1/1,000 of an amp.
<p style="padding-left: 30px;"><em>voltage = (ohms x 1,000) x (amps/1,000)</em></p>
The two factors of 1,000 cancel out so we get:
<p style="padding-left: 30px;"><em>voltage = ohms x amps</em></p>
This experiment introduces <a title="Ohm’s Law" href="ohms-law/">Ohm’s Law</a>.