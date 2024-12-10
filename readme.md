## Bivariate Map Example of Pardoned Turkeys by U.S. State
This map visualizes the origins of turkeys pardoned by U.S. Presidents from the Clinton administration onward. The map uses a bivariate choropleth representation to show the number of turkeys pardoned per state, with color variations indicating the frequency of pardons. The map also overlays turkey origins as points, visualized using custom markers, to showcase specific turkey pardons by state and year. Data is sourced from a variety of public datasets, with each state's pardoned turkey count and origin location displayed interactively.

The bivariate map uses the chroma.js library for color scales, and the leaflet.js library for interactive mapping. The Leaflet popup binds details of each turkey, such as the president who pardoned it, its year of pardoning, and the state of origin. A custom Leaflet control is used to display a legend showing the choropleth color palette for turkey pardons per state.

## Packages, Stylesheets, and Data
- **Leaflet.js** (for map creation and customization)
- **Chroma.js** (for color conversions and color scales)
- **FontAwesome** (for custom icons and markers)
- **Leaflet-ajax** (for loading GeoJSON data)
- **Google Fonts** (for styling text)

**Data Provided by:**

- U.S. Presidents Turkey Pardons data sourced from public datasets (e.g., Wikipedia, historical records) and created in ArcGIS Pro
- U.S. State boundaries in GeoJSON format sourced from [Open Data Portals]
