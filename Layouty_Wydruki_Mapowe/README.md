*english version below*

## Layouty, Wizualizacje i Wydruki Mapowe

### Dashboard Geowizualizacje - Gapminder, Rzym, Ararat
**Autorka:** Agata Ćwikła | **2026**

Interaktywny dashboard zbudowany w R (flexdashboard) łączący cztery typy wizualizacji danych.

Dane socjoekonomiczne pochodzą z pakietu gapminder (PKB per capita i oczekiwana długość życia, 1952–2007); dane przestrzenne pobrano z OpenStreetMap przez Overpass API; model terenu wygenerowano z danych NASA SRTM GL1.

Wyniki i wykorzystane technologie: wykresy ggplot2 i subploty boxplotowe (patchwork), animowany wykres bąbelkowy plotly z trajektoriami wybranych krajów, interaktywna mapa leaflet z punktami gastronomicznymi wokół Koloseum oraz trójwymiarowy model terenu góry Ararat w rayshaderze.

`R` · `flexdashboard` · `ggplot2` · `plotly` · `leaflet` · `rayshader` · `NASA SRTM` · `OpenStreetMap`

---


### Szczegółowa Mapa Geologiczna - arkusz „Rzeki" (Szczawa)
**Autorki:** Agata Ćwikła, Zuzanna Chaniewska, Zuzanna Dybcio, Zofia Gil, Maria Gąsiorowska | **2025**

Szczegółowa mapa geologiczna w skali 1:10 000 wykonana na podstawie tygodniowych ćwiczeń terenowych w okolicach Szczawy (Gorce, lipiec 2025).
Dane terenowe zbierano przy użyciu ArcGIS Field Maps i synchronizowano do ArcGIS Online; mapę końcową wykonano w ArcGIS Pro.
Wyniki i wykorzystane technologie: mapa z wydzieleniami litostratygraficznymi i elementami tektonicznymi (uskoki, nasunięcia) razem z opisem geologicznym.
`ArcGIS Pro` · `ArcGIS Field Maps` · `ArcGIS Online`

---

### Mapa intensywności pożaru - Portugalia 2018
**Autorka:** Agata Ćwikła | **2025**

Mapa przedstawiająca zasięg i ciężkość pożaru z lipca 2018 roku w Portugalii na podstawie analizy dNBR z danych Sentinel-2.
Do obliczenia dNBR wykorzystano obrazy sprzed pożaru (19 lipca 2018) i po pożarze (23 sierpnia 2018).
Wyniki i wykorzystane technologie: layout mapowy z klasyfikacją dNBR, opisem metodyki i mapką poglądową lokalizacji.
`ArcGIS Pro` · `Sentinel-2` · `Copernicus Data Space` `

---

## Layouts, Visualisations and Map Prints

### Dashboard Geowizualizacje - Gapminder, Rzym, Ararat
**Author:** Agata Ćwikła | **2026**

Interactive dashboard built in R (flexdashboard) combining four types of data visualisation.
Socioeconomic data sourced from the gapminder package (GDP per capita and life expectancy, 1952–2007); spatial data retrieved from OpenStreetMap via the Overpass API; terrain model generated from NASA SRTM GL1 data.
Results and technologies used: ggplot2 scatter plots and boxplot subplots (patchwork), animated plotly bubble chart with trajectories of selected countries, interactive leaflet map of food and water points around the Colosseum, and a 3D terrain model of Mount Ararat rendered in rayshader.
`R` · `flexdashboard` · `ggplot2` · `plotly` · `leaflet` · `rayshader` · `NASA SRTM` · `OpenStreetMap`

---

### Szczegółowa Mapa Geologiczna - arkusz „Rzeki" (Szczawa)
**Authors:** Agata Ćwikła, Zuzanna Chaniewska, Zuzanna Dybcio, Zofia Gil, Maria Gąsiorowska | **2025**

Detailed geological map at a scale of 1:10 000 produced on the basis of a week-long field survey near Szczawa (Gorce Mountains, July 2025).
Field data were collected using ArcGIS Field Maps and synchronised to ArcGIS Online; the final map was produced in ArcGIS Pro.
Results and technologies used: map with lithostratigraphic units and tectonic elements (faults, thrust faults) along with a geological description.
`ArcGIS Pro` · `ArcGIS Field Maps` · `ArcGIS Online`

---

###  Mapa intensywności pożaru - Portugalia 2018
**Author:** Agata Ćwikła | **2025**

Map showing the extent and severity of the July 2018 wildfire in Portugal based on dNBR analysis from Sentinel-2 imagery.
Pre-fire (19 July 2018) and post-fire (23 August 2018) images were used to calculate dNBR.
Results and technologies used: map layout with dNBR classification, methodology description and an overview location map.
`ArcGIS Pro` · `Sentinel-2` · `Copernicus Data Space`
