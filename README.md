# peRReo

Who doesn't listen to reggaeton to survive the hours spent in editing a single graph in ggplot? Now you can complete your experience using color palettes based on reggaeton/latin artists for your graphs in R. 

These palettes have been created from the album covers' colors using the [`paletter`](https://github.com/AndreaCirilloAC/paletter) package for palette extraction, and edited manually to improve both aesthetics and inclusivity. All continuous palettes except for "ozuna" and "rosalia" have been successfully checked for color-blind safety using [Chroma.js Color Palette Helper](https://gka.github.io/palettes/#/9|s|00429d,96ffea,ffffe0|ffffe0,ff005e,93003a|1|1). 

The structure of the code was inspired by the awesome [`PNWColors`](https://github.com/jakelawlor/PNWColors) package by Jake Lawlor. 

Disclaimer: the selection of artists is subjective and based on the author's preferences, additional suggestions are welcome. The selection of albums for each artist has been based on the colors of their cover rather than their quality or representativeness.




[Installation](#install-package)  
[Palettes](#palettes)  
[Functions](#building-palettes)  
[Examples](#example-plots)  
[Contact](#contact)  



## Install Package

```r
# Currently available from GitHub:
install.packages("devtools") 
devtools::install_github("jbgb13/peRReo") 
```

## Palettes

### Aventura
<img src="PalettePics/aventura.png">
- Aventura | The Last (2009)

***

### Bad Bunny 1
<img src="PalettePics/badbunny1.png">
- Bad Bunny | YHLQMDLG (2020)

***

### Bad Bunny 2
<img src="PalettePics/badbunny2.png">
- Bad Bunny | El Último Tour del Mundo (2020)

***

### Bad Gyal
<img src="PalettePics/badgyal.png">
- Bad Gyal | Slow Wine Mixtape (2016)

***

### Becky G
<img src="PalettePics/beckyg.png">
- Becky G | Mala Santa (2019)

***

### Calle 13
<img src="PalettePics/calle13.png">
- Calle 13 | Calle 13 (2005)

***

### Daddy Yankee 1
<img src="PalettePics/daddy1.png">
- Daddy Yankee | Talento de Barrio (2008)

***

### Daddy Yankee 2
<img src="PalettePics/daddy2.png">
- Daddy Yankee & Los de la Nazza | King Daddy (2013)

***

### Don Omar
<img src="PalettePics/don.png">
- Don Omar | The Last Don (2003)

***

### Ivy Queen
<img src="PalettePics/ivyqueen.png">
- Ivy Queen | Musa (2012)

***

### Karol G
<img src="PalettePics/karolg.png">
- Karol G | KG0516 (2021)

***

### Natti Natasha
<img src="PalettePics/natti.png">
- Natti Natasha | Iluminatti (2019)

***

### Nicky Jam
<img src="PalettePics/nicky.png">
- Nicky Jam | Infinity (2021)

***

### Ozuna
<img src="PalettePics/ozuna.png">
- Ozuna | Este Loko (2021)

***

### Rosalia
<img src="PalettePics/rosalia.png">
- Rosalia | El Mal Querer (2018)

***

### Shakira
<img src="PalettePics/shakira.png">
- Shakira | Oral Fixation vol. 2 (2005)

***

### Wisin & Yandel
<img src="PalettePics/wyy.png">
- Wisin & Yandel | Los Extraterrestres (2007)

***

## Building Palettes








