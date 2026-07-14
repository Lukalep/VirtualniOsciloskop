# Virtualni osciloskop

## Autori

Projekat su razvili:

* Lazar Jakšić
* Boris Gavranić
* Luka Lepojević

Ovaj projekat predstavlja softversko rešenje razvijeno u grafičkom razvojnom okruženju LabVIEW, namenjeno vizuelizaciji, akviziciji i osnovnoj obradi električnih signala u realnom vremenu[cite: 1]. Sistem simulira funkcionalnost tradicionalnog osciloskopa koristeći hardversku podršku NI USB-5133 digitalizatora.

## Ključne funkcionalnosti

* **Fleksibilno okidanje (Triggering)**: Sistem podržava pet režima okidanja: *Immediate*, *Edge*, *Hysteresis*, *Digital* i *Window*, čime se postiže visoka stabilnost prikaza talasnog oblika.
* **Analiza signala**:
    * Automatsko izdvajanje karakteristika signala (*Amplitude and Level Measurements*).
    * Proračun *Peak-to-Peak* (Vpp) vrednosti signala.
* **Napredna frekvencijska analiza**:
    * **FFT Mag Phase**: Transformacija signala u frekvencijski domen uz prikaz amplitude i faze.
    * **PSD (Power Spectral Density)**: Procena spektralne gustine snage za analizu šuma i harmonika.
* **Real-time vizuelizacija**: Pregledan prikaz signala na *Waveform Graph* indikatoru uz stalnu proveru statusa grešaka i bezbedno upravljanje sesijom.

## Tehnologije

* **Razvojno okruženje**: LabVIEW.
* **Hardver**: NI USB-5133.
* **Komunikacija**: NI-SCOPE drajveri.
