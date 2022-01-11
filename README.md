# SSD1327_MOD per progetti in PlatformIO / VS Code
Versione di Adafruit_SSD1327 adattata per display del laboratorio.

## Cosa cambia rispetto al file Adafruit_SSD1327.cpp
Il display in dotazione al laboratorio non viene inizializzato correttamente dal file originale della libreria Adafruit SSD1327.
Questo file contiene la sequenza di inizializzazione corretta per il nostro display SSD1327.

## Dove installare il file Adafruit_SSD1327.cpp
Questo file deve _sostituire_ il file originale che si trova in  <nome_progetto>\\.pio\libdeps\release\Adafruit SSD1327\Adafruit_SSD1327.cpp
