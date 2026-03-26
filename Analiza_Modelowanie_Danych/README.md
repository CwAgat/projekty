## Folder: Analiza_Modelowanie_Danych

Projekty zaliczeniowe z zakresu analizy danych środowiskowych i przestrzennych — AGH Kraków, kierunek Geoinformatyka.

---

### Analiza_korelacji_przyrost_modrzewia
**Autorki:** Agata Ćwikła, Zofia Gil, Joanna Heyda | **2025**
**Temat:** "Wykorzystanie analizy korelacji w badaniach wpływu czynników klimatycznych na przyrost roczny drzew."

Analiza zależności między warunkami klimatycznymi a przyrostem rocznym modrzewia europejskiego w trzech lokalizacjach na Litwie (dane NOAA + CRU TS, lata 1901–2006).
Zastosowano analizę korelacji stacjonarnej i ruchomej oraz analizę punktów zmian.
Wyniki i wykorzystane technologie: wykresy korelacji i klimatogramy, `R`(`ggplot2` , `dplR`) · `ArcGIS Pro`, `LateX`

---

### 🌫️ Analiza zmienności zanieczyszczenia powietrza PM2.5 w Krakowie
**Autorki:** Agata Ćwikła, Zofia Gil, Joanna Heyda | **2026**

Analiza przestrzenna stężeń PM2.5 w Krakowie na podstawie danych z czujników Airly pobranych przez API udostępniane przez firme Airly dla wybranych godzin w weekend i dni robocze (styczeń 2026).
Interpolacja przestrzenna metodą krigingu z porównaniem modeli semiwariogramu.
Wyniki i wykorzystane technologie: mapy predykcji stężeń i temperatury z oceną jakości dopasowania modeli.
`R`(`sp`,`sf`,`spatstat`), `API Airly` · kriging · `LateX`

---

### 🧊 Modelowanie zmian zasięgu pokrywy lodowej — biegun południowy
**Autorki:** Agata Ćwikła, Zofia Gil | **2025**

Analiza i modelowanie zmian zasięgu lodu morskiego wokół Antarktydy w latach 1978–2009.
Dopasowanie modelu do danych; animacja porównująca dane rzeczywiste z wymodelowanymi.
Wyniki i wykorzystane technologie: animacja czasoprzestrzenna zasięgu lodu.
`R` · `Python` · `FFmpeg` · `LateX`

---

### 🔬 Analiza_obrazow_zawartosc_mineralow
**Autorka:** Agata Ćwikła | **2026**
**Temat:** Analiza zawartości minerałów w piaskowcu godulskim

Automatyczna detekcja i pomiar powierzchni glaukonitu i kwarcu w obrazach mikroskopowych na podstawie segmentacji HSV i operacji morfologicznych.
Wyznaczenie ilości minerałów w skale, obliczenie rzeczywistych pól powierzchni.
Wyniki i wykorzystane technologie: obraz wynikowy z wydzielonymi minerałami i zmierzonymi powierzchniami.
`MATLAB` · przetwarzanie obrazów · morfologia matematyczna · `LateX`