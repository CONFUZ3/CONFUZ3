<a href="https://www.mahadimran.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.jpg">
    <img alt="Mahad Imran. GeoAI, GIS and spatial optimization. Name set over 25 m contour lines of the Margalla Hills, Islamabad." src="assets/banner-light.jpg" width="100%">
  </picture>
</a>

<p align="center">
  <a href="https://www.mahadimran.com"><img src="https://img.shields.io/badge/Website-mahadimran.com-111111?style=flat-square&logo=googlechrome&logoColor=white" alt="Website"></a>
  <a href="https://www.linkedin.com/in/mahadimran29"><img src="https://img.shields.io/badge/LinkedIn-mahadimran29-0A66C2?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0zIDloNHYxMkgzek01IDNhMiAyIDAgMSAxIDAgNCAyIDIgMCAwIDEgMC00ek05IDloMy44djEuN2guMWMuNS0xIDEuOC0yIDMuOC0yIDQgMCA0LjggMi42IDQuOCA2VjIxaC00di01LjZjMC0xLjMgMC0zLTEuOS0zcy0yLjEgMS40LTIuMSAyLjlWMjFIOXoiLz48L3N2Zz4%3D" alt="LinkedIn"></a>
  <a href="https://scholar.google.com/citations?user=FK3-KdkAAAAJ"><img src="https://img.shields.io/badge/Google_Scholar-Mahad_Imran-4285F4?style=flat-square&logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
  <a href="https://orcid.org/0009-0005-8066-8901"><img src="https://img.shields.io/badge/ORCID-0009--0005--8066--8901-A6CE39?style=flat-square&logo=orcid&logoColor=white" alt="ORCID"></a>
  <a href="mailto:mahad.imran29@gmail.com"><img src="https://img.shields.io/badge/Email-Say_hi-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

I'm a **geospatial data scientist and GIS consultant**. I work on **spatial optimization**, **location intelligence** and **GeoAI**: picking which neighbourhoods a store should open in, or where a city should put its fire stations so help arrives in time. I also use LLMs to automate the slow, repetitive parts of GIS.

Before GIS I spent five years building education startups in Pakistan and coached 300+ people into jobs. I still think like a founder: ship something useful, then make it rigorous.

### 🔭 Currently

- 📄 **New paper:** [SOCA: A Conversational Agent for Facility Location Problems](https://doi.org/10.3390/ijgi15110494), out in *ISPRS IJGI* (2026)
- 🧭 Building tools that let planners describe siting problems in plain English and get exact answers back
- ✍️ Writing practical, tested GIS guides at [mahadimran.com/blog](https://www.mahadimran.com/blog)
- 🤝 Open to GIS consulting and research collaborations

### 📄 Research: SOCA

<a href="https://github.com/CONFUZ3/SOCA"><img src="assets/soca.jpg" alt="The SOCA web app solving a Manhattan firehouse coverage problem: datasets on the left, a map with five selected firehouses and their 1 km service areas in the middle, and the agent's explanation of coverage and equity on the right." width="100%"></a>

Describe a siting problem in plain English and [**SOCA**](https://github.com/CONFUZ3/SOCA) solves it exactly. The LLM only picks the formulation and extracts parameters through schema-checked function calls. Deterministic tools fetch boundaries, population and road networks from open data, then solve P-Median, P-Center, MCLP or LSCP, matching the `spopt` reference optima on all four. [Read the paper →](https://doi.org/10.3390/ijgi15110494)

### 📌 More projects

| Project | What it does | Stack |
| --- | --- | --- |
| [**sen2auto**](https://github.com/CONFUZ3/sen2auto) | Sentinel-2 pipeline for provincial-scale crop monitoring. Mosaics across UTM zones with cloud-aware compositing and computes NDVI, NDRE and GNDVI. | Python, rasterio, GeoPandas, Streamlit |
| [**GeoLint**](https://github.com/CONFUZ3/geolint) | Linter and auto-formatter for spatial data. Validates geometry, catches CRS mismatches and repairs invalid shapes in batch. | Python, Shapely, GeoPandas, Streamlit |
| [**LLM-SDSS**](https://github.com/CONFUZ3/llm-sdss) | Spatial decision support from plain-English criteria. Runs weighted overlay and returns ranked sites with a map and PDF report. | Python, PostGIS, Gemini API |
| [**ClickyWindows**](https://github.com/CONFUZ3/ClickyWindows) | Push-to-talk AI voice companion for Windows that flies its cursor to whatever it mentions on screen. | C#, .NET 8, Gemini Live API |
| [**EstateView**](https://github.com/CONFUZ3/EstateView) | GIS dashboard for exploring real estate plots, sectors and roads with live filtering. | React, MapLibre GL, shpjs |

### 🕹️ Play with a map

**[Site Selection Showdown](https://www.mahadimran.com/site-selection)**: be the fire chief. Place stations in Islamabad, Bahawalpur or Calgary, then reveal the optimal plan and see how close you got.

<a href="https://www.mahadimran.com/site-selection"><img src="assets/site-selection-reveal.png" alt="Site Selection Showdown in Islamabad: four player-placed fire stations protect 1,130,394 people, while the optimal plan's four red-starred stations would protect 1,799,739. Score 63%." width="100%"></a>

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://www.mahadimran.com/true-size"><img src="assets/true-size.png" alt="True Size Map: Greenland dragged down to central Africa, where it shrinks to its real size, next to its inflated outline in the Arctic."></a>
      <br><b><a href="https://www.mahadimran.com/true-size">True Size Map</a></b><br>
      <sub>Drag Greenland to the equator and watch it shrink. Then compare Mercator, Equal Earth, Robinson and more.</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://www.mahadimran.com/punjab-education"><img src="assets/punjab-education.png" alt="Punjab Education Map: a choropleth of women's literacy across Punjab's 36 districts, ranging from 26.1% to 78.3%."></a>
      <br><b><a href="https://www.mahadimran.com/punjab-education">Punjab Education Map</a></b><br>
      <sub>30+ education indicators across Punjab's 36 districts, from literacy to gender parity.</sub>
    </td>
  </tr>
</table>

### ✍️ Recent writing

- [The Fastest Point-in-Polygon Join in Python, Benchmarked to 10 Million Points](https://www.mahadimran.com/blog/point-in-polygon-python-benchmark)
- [Can LLMs Do GIS? Where They Fail, and the Pattern That Works](https://www.mahadimran.com/blog/can-llms-do-gis)
- [Which H3 Resolution Should You Use?](https://www.mahadimran.com/blog/h3-hexagon-resolution-guide)
- [Fire Station Location Analysis: How Coverage Models Decide Where Stations Go](https://www.mahadimran.com/blog/fire-station-location-analysis)
- [Shapefile vs GeoPackage vs GeoParquet vs FlatGeobuf vs GeoJSON, Benchmarked](https://www.mahadimran.com/blog/geospatial-file-formats-compared)

➡️ [All articles](https://www.mahadimran.com/blog)

### 🧰 Toolbox

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square&logo=pandas&logoColor=white" alt="GeoPandas">
  <img src="https://img.shields.io/badge/PostGIS-336791?style=flat-square&logo=postgresql&logoColor=white" alt="PostGIS">
  <img src="https://img.shields.io/badge/QGIS-589632?style=flat-square&logo=qgis&logoColor=white" alt="QGIS">
  <img src="https://img.shields.io/badge/MapLibre_GL-396CB2?style=flat-square&logo=maplibre&logoColor=white" alt="MapLibre GL">
  <img src="https://img.shields.io/badge/OpenStreetMap-7EBC6F?style=flat-square&logo=openstreetmap&logoColor=white" alt="OpenStreetMap">
  <img src="https://img.shields.io/badge/D3-F9A03C?style=flat-square&logo=d3&logoColor=white" alt="D3">
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit">
  <img src="https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini API">
  <img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="C#">
</p>

**Also:** Shapely · rasterio · OSMnx · H3 · spopt · PuLP · Sentinel-2 · Landsat · LLM function calling

---

<p align="center">
  <sub>📍 Islamabad, Pakistan · 33.6844° N, 73.0479° E<br>Off the clock: coffee, education, and CS2. If you want to talk maps, ask me anything.</sub>
</p>
