### Issues with NREL Fuel Station Locator Widget

1. The station-locator widget overwrites other hash values when auto-refreshing the URL on the initial load.  
An extra slash is inserted after the # symbol.  
Example: watch the existing hash values disappear here when hitting refresh:  <a href="../nrel/#show=vehicles">Attempt to include local site's hash value</a>

2. NREL has not yet implemented corrections submitted July 20, 2021 for two Georgia locations displayed outside the state.

3. Margins are need in footer to the left of "iPhone App" and to the right of "Alternative Fuels Data Center". Also add padding to the left of "Loading..." text notice, but not to the left of the widget itself.   

4. The use of black for the lower bar looks like the end of the page and breaks up the flow. Consider placing the source credit in the upper right, top justified with the top tabs.  

5. Map zooms when scrolling over. Considering adding a map click to toggle on zoom-on-scroll. (Try clicking second map on page for example.)  

