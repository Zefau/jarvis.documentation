
## Gewerk Sonstige (`_defaults`)

### vordefinierte Datenpunkte

<table><thead><tr><th>Datenpunkt Bezeichner</th><th>Datenpunkt Stil</th><th>Anzeige</th><th>Einheit</th><th>Icon</th><th>Icon Stil</th></tr></thead>
<tbody><tr><td><code>battery</code></td><td>-</td><td>-</td><td><code>"&nbsp;%"</code></td><td><code>{<br />&nbsp;">80":&nbsp;"battery-high",<br />&nbsp;"<=80":&nbsp;"battery-medium",<br />&nbsp;"<=30":&nbsp;"battery-low",<br />&nbsp;"<=10":&nbsp;"battery-outline&nbsp;blink",<br />&nbsp;"<=5":&nbsp;"battery-alert-variant-outline&nbsp;blink"<br />}</code></td><td><code>{<br />&nbsp;"<=10":&nbsp;{<br />&nbsp;&nbsp;"color":&nbsp;"#900"<br />&nbsp;}<br />}</code></td></tr></tbody>
<tbody><tr><td><code>firmware</code></td><td>-</td><td><code>{<br />&nbsp;"true":&nbsp;"Update&nbsp;verfügbar",<br />&nbsp;"false":&nbsp;"kein&nbsp;Update"<br />}</code></td><td>-</td><td><code>{<br />&nbsp;"true":&nbsp;"mdi-cog-refresh",<br />&nbsp;"false":&nbsp;"mdi-cog-outline"<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>frost</code></td><td>-</td><td>-</td><td>-</td><td><code>{<br />&nbsp;"default":&nbsp;"mdi-snowflake"<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>humidity</code></td><td>-</td><td>-</td><td><code>"&nbsp;%"</code></td><td><code>"water-percent"</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>illuminance</code></td><td>-</td><td>-</td><td><code>"&nbsp;lux"</code></td><td>-</td><td>-</td></tr></tbody>
<tbody><tr><td><code>level</code></td><td>-</td><td>-</td><td><code>"&nbsp;%"</code></td><td>-</td><td>-</td></tr></tbody>
<tbody><tr><td><code>lowbattery</code></td><td><code>{<br />&nbsp;"true":&nbsp;{<br />&nbsp;&nbsp;"color":&nbsp;"#900",<br />&nbsp;&nbsp;"fontWeight":&nbsp;"bold"<br />&nbsp;},<br />&nbsp;"false":&nbsp;{<br />&nbsp;&nbsp;"color":&nbsp;"#999"<br />&nbsp;}<br />}</code></td><td><code>{<br />&nbsp;"true":&nbsp;"niedrig",<br />&nbsp;"false":&nbsp;"voll"<br />}</code></td><td>-</td><td><code>{<br />&nbsp;"true":&nbsp;"battery-alert-variant-outline",<br />&nbsp;"false":&nbsp;"battery-high"<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>position</code></td><td>-</td><td>-</td><td>-</td><td><code>"map-marker"</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>power</code></td><td>-</td><td>-</td><td>-</td><td><code>"power"</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>config</code></td><td>-</td><td>-</td><td>-</td><td><code>{<br />&nbsp;"default":&nbsp;"mdi-cog"<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>connectivity</code></td><td>-</td><td>-</td><td>-</td><td><code>{<br />&nbsp;"default":&nbsp;"mdi-wifi-arrow-left-right"<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>reachability</code></td><td><code>{<br />&nbsp;"true":&nbsp;{<br />&nbsp;&nbsp;"color":&nbsp;"#090"<br />&nbsp;},<br />&nbsp;"false":&nbsp;{<br />&nbsp;&nbsp;"color":&nbsp;"#900",<br />&nbsp;&nbsp;"fontWeight":&nbsp;"bold"<br />&nbsp;}<br />}</code></td><td><code>{<br />&nbsp;"true":&nbsp;"erreichbar",<br />&nbsp;"false":&nbsp;"nicht&nbsp;erreichbar"<br />}</code></td><td>-</td><td><code>{<br />&nbsp;"true":&nbsp;"lan-connect",<br />&nbsp;"false":&nbsp;"lan-disconnect"<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>rssi</code></td><td>-</td><td>-</td><td>-</td><td><code>{<br />&nbsp;"default":&nbsp;"mdi-antenna"<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>temperature</code></td><td>-</td><td>-</td><td><code>"&nbsp;°C"</code></td><td><code>"thermometer"</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>trigger</code></td><td>-</td><td>-</td><td>-</td><td><code>"power"</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>unreach</code></td><td><code>{<br />&nbsp;"true":&nbsp;{<br />&nbsp;&nbsp;"color":&nbsp;"#900",<br />&nbsp;&nbsp;"fontWeight":&nbsp;"bold"<br />&nbsp;},<br />&nbsp;"false":&nbsp;{<br />&nbsp;&nbsp;"color":&nbsp;"#090"<br />&nbsp;}<br />}</code></td><td><code>{<br />&nbsp;"true":&nbsp;"nicht&nbsp;erreichbar",<br />&nbsp;"false":&nbsp;"erreichbar"<br />}</code></td><td>-</td><td><code>{<br />&nbsp;"true":&nbsp;"lan-disconnect",<br />&nbsp;"false":&nbsp;"lan-connect"<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>wind</code></td><td>-</td><td>-</td><td><code>"&nbsp;km/h"</code></td><td><code>"weather-windy"</code></td><td>-</td></tr></tbody>
</table>

<h3>Beispielkonfiguration


#### Adapter hm-rpc

<h5>HM-LC-Sw1PBU-FM</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>powerCh1</td>
<td><code>.1.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.STATE</code></td>
</tr>
<tr>
<td><code>powerCh2</td>
<td><code>.2.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.2.STATE</code></td>
</tr>
<tr>
<td><code>powerCh3</td>
<td><code>.3.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.3.STATE</code></td>
</tr>
<tr>
<td><code>powerCh4</td>
<td><code>.4.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.4.STATE</code></td>
</tr>
<tr>
<td><code>powerCh5</td>
<td><code>.5.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.5.STATE</code></td>
</tr>
<tr>
<td><code>powerCh6</td>
<td><code>.6.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.6.STATE</code></td>
</tr>
<tr>
<td><code>powerCh7</td>
<td><code>.7.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.7.STATE</code></td>
</tr>
<tr>
<td><code>powerCh8</td>
<td><code>.8.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.8.STATE</code></td>
</tr>
<tr>
<td><code>powerCh9</td>
<td><code>.9.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.9.STATE</code></td>
</tr>
<tr>
<td><code>powerCh10</td>
<td><code>.10.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.10.STATE</code></td>
</tr>
<tr>
<td><code>powerCh11</td>
<td><code>.11.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.11.STATE</code></td>
</tr>
<tr>
<td><code>powerCh12</td>
<td><code>.12.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.12.STATE</code></td>
</tr>
<tr>
<td><code>powerCh13</td>
<td><code>.13.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.13.STATE</code></td>
</tr>
<tr>
<td><code>powerCh14</td>
<td><code>.14.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.14.STATE</code></td>
</tr>
<tr>
<td><code>powerCh15</td>
<td><code>.15.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.15.STATE</code></td>
</tr>
<tr>
<td><code>powerCh16</td>
<td><code>.16.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.16.STATE</code></td>
</tr>
</tbody></table>

#### Adapter mihome-vacuum

<h5>state</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>0</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>1</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>2</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>3</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>4</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>5</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>6</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>7</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>8</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>9</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>10</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>action</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>0</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>1</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>2</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>3</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>4</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>5</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>6</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>7</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>8</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>9</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>10</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>11</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>12</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>13</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>14</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>15</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>16</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>17</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>18</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### Adapter mqtt

<h5>version</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>0</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>1</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>reachability</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>0</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>1</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>2</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>3</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>4</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>5</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>ip</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>0</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>1</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>2</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>3</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>4</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>5</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>6</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>7</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>8</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>9</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>10</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>11</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>12</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>13</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>14</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>signal</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>0</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>1</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>2</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>3</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>4</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>5</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>6</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>7</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>8</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>9</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>10</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>11</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>dataReceived</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>0</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>1</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>2</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>3</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>4</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>5</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>6</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>7</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>8</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>9</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>10</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>11</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>12</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>13</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>14</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>15</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>power</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>action</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>powerCurrent</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>unit</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>powerMeter</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>unit</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>powerConsumption</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>unit</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>powerConsumptionToday</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>unit</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>powerConsumptionYesterday</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>unit</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>power1</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>action</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>power2</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>action</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>power3</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>action</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>power4</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>action</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>power5</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>action</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>power6</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>action</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>power7</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>action</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>power8</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>action</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>power9</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>action</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### Adapter nuki-extended

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>door</td>
<td><code>.state.closed</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>doorState</td>
<td><code>.state.doorState</code></td>
<td><code></code></td>
<td><code>{<br />&nbsp;"0":&nbsp;"UNAVAILABLE",<br />&nbsp;"1":&nbsp;"DEACTIVATED",<br />&nbsp;"2":&nbsp;"DOOR_CLOSED",<br />&nbsp;"3":&nbsp;"DOOR_OPENED",<br />&nbsp;"4":&nbsp;"DOOR_STATE_UNKNOWN",<br />&nbsp;"5":&nbsp;"CALIBRATING"<br />}</code></td>
<td><code></code></td>
</tr>
<tr>
<td><code>lock</td>
<td><code>.state.locked</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>lockState</td>
<td><code>.state.lockState</code></td>
<td><code></code></td>
<td><code>{<br />&nbsp;"0":&nbsp;"UNCALIBRATED",<br />&nbsp;"1":&nbsp;"LOCKED",<br />&nbsp;"2":&nbsp;"UNLOCKING",<br />&nbsp;"3":&nbsp;"UNLOCKED",<br />&nbsp;"4":&nbsp;"LOCKING",<br />&nbsp;"5":&nbsp;"UNLATCHED",<br />&nbsp;"6":&nbsp;"UNLOCKED_LOCK_N_GO",<br />&nbsp;"7":&nbsp;"UNLATCHING",<br />&nbsp;"254":&nbsp;"MOTOR_BLOCKED",<br />&nbsp;"255":&nbsp;"UNDEFINED"<br />}</code></td>
<td><code></code></td>
</tr>
<tr>
<td><code>lockUpdate</td>
<td><code>.state.lastStateUpdate</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>lowbattery</td>
<td><code>.state.batteryCritical</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>ACTIONS</td>
<td><code></code></td>
<td><code></code></td>
<td><code>{<br />&nbsp;"0":&nbsp;"NO_ACTION",<br />&nbsp;"1":&nbsp;"UNLOCK",<br />&nbsp;"2":&nbsp;"LOCK",<br />&nbsp;"3":&nbsp;"UNLATCH",<br />&nbsp;"4":&nbsp;"LOCK_N_GO",<br />&nbsp;"5":&nbsp;"LOCK_N_GO_WITH_UNLATCH"<br />}</code></td>
<td><code>._ACTION</code></td>
</tr>
<tr>
<td><code>LOCK</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code>._ACTION.LOCK</code></td>
</tr>
<tr>
<td><code>LOCK_N_GO</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code>._ACTION.LOCK_N_GO</code></td>
</tr>
<tr>
<td><code>LOCK_N_GO_WITH_UNLATCH</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code>._ACTION.LOCK_N_GO_WITH_UNLATCH</code></td>
</tr>
<tr>
<td><code>UNLATCH</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code>._ACTION.UNLATCH</code></td>
</tr>
<tr>
<td><code>UNLOCK</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code>._ACTION.UNLOCK</code></td>
</tr>
</tbody></table>

#### Adapter tr-064

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>ab</td>
<td><code>.ab</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>ip</td>
<td><code>.externalIP</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>ipv6</td>
<td><code>.externalIPv6</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>reboot</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code>.reboot</code></td>
</tr>
<tr>
<td><code>reconnect</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code>.reconnectInternet</code></td>
</tr>
<tr>
<td><code>wlan24</td>
<td><code>.wlan24</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>wlan50</td>
<td><code>.wlan50</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### Adapter unifi

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>update_available</td>
<td><code>.update_available</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>version</td>
<td><code>.version</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### Adapter zwave2

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>valve</td>
<td><code>.Multilevel_Switch.currentValue</code></td>
<td><code>%</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>mode</td>
<td><code>.Thermostat_Mode.mode</code></td>
<td><code></code></td>
<td></td>
<td><code>.Thermostat_Mode.mode</code></td>
</tr>
<tr>
<td><code>setTemperatureEnergySave</td>
<td><code>.Thermostat_Setpoint.setpoint_energySaveHeating</code></td>
<td><code>°C</code></td>
<td></td>
<td><code>.Thermostat_Setpoint.setpoint_energySaveHeating</code></td>
</tr>
<tr>
<td><code>temperature</td>
<td><code>.Multilevel_Sensor.airTemperature</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>setTemperature</td>
<td><code>.Thermostat_Setpoint.setpoint_heating</code></td>
<td><code></code></td>
<td></td>
<td><code>.Thermostat_Setpoint.setpoint_heating</code></td>
</tr>
</tbody></table>