
# Gewerk Steckdose (`socket`)

## vordefinierte Datenpunkte

<table><thead><tr><th>Datenpunkt Bezeichner</th><th>Datenpunkt Stil</th><th>Anzeige</th><th>Einheit</th><th>Icon</th><th>Icon Stil</th></tr></thead>
<tbody><tr><td><code>power</code></td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td></tr></tbody>
<tbody><tr><td><code>consumption</code></td><td>-</td><td>-</td><td><code>&quot;&nbsp;W&quot;</code></td><td><code>{<br />&nbsp;&quot;default&quot;:&nbsp;&quot;mdi-power-plug-off-outline&quot;,<br />&nbsp;&quot;&gt;0&quot;:&nbsp;&quot;mdi-power-plug&quot;<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>meter</code></td><td>-</td><td>-</td><td><code>&quot;&nbsp;W&quot;</code></td><td><code>{<br />&nbsp;&quot;default&quot;:&nbsp;&quot;mdi-power-plug-off-outline&quot;,<br />&nbsp;&quot;&gt;0&quot;:&nbsp;&quot;mdi-power-plug&quot;<br />}</code></td><td>-</td></tr></tbody>
</table>

## Beispielkonfiguration


### Adapter hm-rpc


#### HmIP-FSM

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>power</td>
<td><code>.2.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.2.STATE</code></td>
</tr>
<tr>
<td><code>timerOff</td>
<td><code>.2.ON_TIME</code></td>
<td><code></code></td>
<td></td>
<td><code>.2.ON_TIME</code></td>
</tr>
<tr>
<td><code>powerCurrent</td>
<td><code>.5.CURRENT</code></td>
<td><code> mA</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>powerFrequency</td>
<td><code>.5.FREQUENCY</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>powerCounter</td>
<td><code>.5.ENERGY_COUNTER</code></td>
<td><code> Wh</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>powerMeter</td>
<td><code>.5.POWER</code></td>
<td><code> W</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>powerVoltage</td>
<td><code>.5.VOLTAGE</code></td>
<td><code> V</code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HmIP-PS

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>power</td>
<td><code>.3.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HmIP-PSM

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>power</td>
<td><code>.3.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>meter</td>
<td><code>.6.POWER</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HM-ES-PMSw1-Pl-DN-R1

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>power</td>
<td><code>.1.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.STATE</code></td>
</tr>
<tr>
<td><code>timerOff</td>
<td><code>.1.ON_TIME</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.ON_TIME</code></td>
</tr>
<tr>
<td><code>powerCurrent</td>
<td><code>.2.CURRENT</code></td>
<td><code> mA</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>powerFrequency</td>
<td><code>.2.FREQUENCY</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>powerCounter</td>
<td><code>.2.ENERGY_COUNTER</code></td>
<td><code> Wh</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>powerMeter</td>
<td><code>.2.POWER</code></td>
<td><code> W</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>powerVoltage</td>
<td><code>.2.VOLTAGE</code></td>
<td><code> V</code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HM-LC-Sw1-Pl-2

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>power</td>
<td><code>.1.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.STATE</code></td>
</tr>
<tr>
<td><code>timerOff</td>
<td><code>.1.ON_TIME</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.ON_TIME</code></td>
</tr>
</tbody></table>

#### HM-LC-Sw1-Pl-DN-R1

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>power</td>
<td><code>.1.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.STATE</code></td>
</tr>
<tr>
<td><code>timerOff</td>
<td><code>.1.ON_TIME</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.ON_TIME</code></td>
</tr>
</tbody></table>

#### HM-ES-PMSw1-DR

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>power</td>
<td><code>.1.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.STATE</code></td>
</tr>
<tr>
<td><code>timerOff</td>
<td><code>.1.ON_TIME</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.ON_TIME</code></td>
</tr>
<tr>
<td><code>boot</td>
<td><code>.2.BOOT</code></td>
<td><code></code></td>
<td></td>
<td><code>.2.BOOT</code></td>
</tr>
<tr>
<td><code>powerCurrent</td>
<td><code>.2.CURRENT</code></td>
<td><code> mA</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>powerFrequency</td>
<td><code>.2.FREQUENCY</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>powerCounter</td>
<td><code>.2.ENERGY_COUNTER</code></td>
<td><code> Wh</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>powerMeter</td>
<td><code>.2.POWER</code></td>
<td><code> W</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>powerVoltage</td>
<td><code>.2.VOLTAGE</code></td>
<td><code> V</code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HM-ES-PMSw1-Pl

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>power</td>
<td><code>.1.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.STATE</code></td>
</tr>
<tr>
<td><code>timerOff</td>
<td><code>.1.ON_TIME</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.ON_TIME</code></td>
</tr>
<tr>
<td><code>boot</td>
<td><code>.2.BOOT</code></td>
<td><code></code></td>
<td></td>
<td><code>.2.BOOT</code></td>
</tr>
<tr>
<td><code>powerCurrent</td>
<td><code>.2.CURRENT</code></td>
<td><code> mA</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>powerFrequency</td>
<td><code>.2.FREQUENCY</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>powerCounter</td>
<td><code>.2.ENERGY_COUNTER</code></td>
<td><code> Wh</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>powerMeter</td>
<td><code>.2.POWER</code></td>
<td><code> W</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>powerVoltage</td>
<td><code>.2.VOLTAGE</code></td>
<td><code> V</code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

### Adapter hmip


#### HmIP-PS

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>power</td>
<td><code>.channels.1.on</code></td>
<td><code></code></td>
<td></td>
<td><code>.channels.1.on</code></td>
</tr>
</tbody></table>

### Adapter shelly

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>power</td>
<td><code>.Relay0.Switch</code></td>
<td><code></code></td>
<td></td>
<td><code>.Relay0.Switch</code></td>
</tr>
<tr>
<td><code>powerCounter</td>
<td><code>.Relay0.Energy</code></td>
<td><code> Wh</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>powerMeter</td>
<td><code>.Relay0.Power</code></td>
<td><code> W</code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>