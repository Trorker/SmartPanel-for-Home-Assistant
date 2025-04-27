# SmartPanel for Home Assistant

Un'interfaccia touchscreen avanzata per Home Assistant, basata su ESPHome e LVGL, progettata per dispositivi come il JC3248W535.

## Descrizione

Questo progetto offre un pannello di controllo intelligente che visualizza informazioni in tempo reale e consente il controllo di vari dispositivi tramite Home Assistant.  
Utilizza ESPHome con la libreria grafica LVGL per creare un'interfaccia utente reattiva e personalizzabile.

## Caratteristiche

- Visualizzazione di dati in tempo reale come potenza, tensione e temperatura
- Controllo del termostato direttamente dal pannello
- Regolazione della luminosità del display
- Interfaccia utente personalizzabile con LVGL
- Compatibilità con dispositivi ESP32 dotati di display touch

## Ispirazione

Questo progetto è stato ispirato dal video di Іван RIO:  
[Крутий дисплей для Home Assistant | LVGL в ESPHome](https://www.youtube.com/watch?v=efeK-VodNlA)

Codice base di riferimento:  
[ivan-rio/esphome_configs - cyd-lvgl.yaml](https://github.com/ivan-rio/esphome_configs/blob/main/CYD/cyd-lvgl.yaml)

## Requisiti Hardware

- Microcontrollore ESP32 (consigliato con PSRAM)
- Display touchscreen compatibile (es. JC3248W535)
- Alimentazione adeguata per il dispositivo

## Licenza
MIT License

---

Le contribuzioni sono benvenute! Sentiti libero di aprire issue o pull request per migliorare il progetto.
