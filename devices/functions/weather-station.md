
# Gewerk Wetter-Station (`weather-station`)

## vordefinierte Datenpunkte

<table><thead><tr><th>Datenpunkt Bezeichner</th><th>Datenpunkt Stil</th><th>Anzeige</th><th>Einheit</th><th>Icon</th><th>Icon Stil</th></tr></thead>
<tbody><tr><td><code>humidity</code></td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td></tr></tbody>
<tbody><tr><td><code>wind</code></td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td></tr></tbody>
<tbody><tr><td><code>temperature</code></td><td>-</td><td>-</td><td>-</td><td>-</td><td>-</td></tr></tbody>
<tbody><tr><td><code>illumination</code></td><td>-</td><td>-</td><td>-</td><td><code>&quot;mdi-brightness-7&quot;</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>sunshineduration</code></td><td>-</td><td>-</td><td>-</td><td><code>&quot;mdi-weather-sunny&quot;</code></td><td>-</td></tr></tbody>
</table>

## Beispielkonfiguration


### Adapter hm-rpc


#### HmIP-STHO

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>temperature</td>
<td><code>.1.ACTUAL_TEMPERATURE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>humidity</td>
<td><code>.1.HUMIDITY</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HmIP-STHO-A

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>temperature</td>
<td><code>.1.ACTUAL_TEMPERATURE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>humidity</td>
<td><code>.1.HUMIDITY</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HmIP-SWO-B

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>humidity</td>
<td><code>.1.HUMIDITY</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>wind</td>
<td><code>.1.WIND_SPEED</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>temperature</td>
<td><code>.1.ACTUAL_TEMPERATURE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>illumination</td>
<td><code>.1.ILLUMINATION</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>sunshineDuration</td>
<td><code>.1.SUNSHINEDURATION</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HmIP-SWO-PL

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>humidity</td>
<td><code>.1.HUMIDITY</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>wind</td>
<td><code>.1.WIND_SPEED</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>temperature</td>
<td><code>.1.ACTUAL_TEMPERATURE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>illumination</td>
<td><code>.1.ILLUMINATION</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>sunshineDuration</td>
<td><code>.1.SUNSHINEDURATION</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>raining</td>
<td><code>.1.RAINING</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>rainCounter</td>
<td><code>.1.RAIN_COUNTER</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HM-WDS40-TH-I-2

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>temperature</td>
<td><code>.1.TEMPERATURE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>humidity</td>
<td><code>.1.HUMIDITY</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

### Adapter hmip


#### HmIP-STHO

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>temperature</td>
<td><code>.channels.1.actualTemperature</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>humidity</td>
<td><code>.channels.1.humidity</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>vapor</td>
<td><code>.channels.1.vaporAmount</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>display</td>
<td><code>.channels.1.display</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HmIP-STHO-A

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>temperature</td>
<td><code>.1.ACTUAL_TEMPERATURE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>humidity</td>
<td><code>.1.HUMIDITY</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HmIP-SWO-B

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>humidity</td>
<td><code>.1.HUMIDITY</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>wind</td>
<td><code>.1.WIND_SPEED</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>temperature</td>
<td><code>.1.ACTUAL_TEMPERATURE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>illumination</td>
<td><code>.1.ILLUMINATION</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>sunshineduration</td>
<td><code>.1.SUNSHINEDURATION</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>