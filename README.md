# Virtualni osciloskop

## Autori

Projekat su razvili:

* Lazar Jakšić[cite: 1]
* Boris Gavranić[cite: 1]
* Luka Lepojević[cite: 1]

Ovaj projekat predstavlja softversko rešenje razvijeno u grafičkom razvojnom okruženju LabVIEW, namenjeno vizuelizaciji, akviziciji i osnovnoj obradi električnih signala u realnom vremenu[cite: 1]. Sistem simulira funkcionalnost tradicionalnog osciloskopa koristeći hardversku podršku NI USB-5133 digitalizatora[cite: 1].

## Ključne funkcionalnosti

* **Fleksibilno okidanje (Triggering)**: Sistem podržava pet režima okidanja: *Immediate*, *Edge*, *Hysteresis*, *Digital* i *Window*, čime se postiže visoka stabilnost prikaza talasnog oblika[cite: 1].
* **Analiza signala**:
    * Automatsko izdvajanje karakteristika signala (*Amplitude and Level Measurements*)[cite: 1].
    * Proračun *Peak-to-Peak* (Vpp) vrednosti signala[cite: 1].
* **Napredna frekvencijska analiza**:
    * **FFT Mag Phase**: Transformacija signala u frekvencijski domen uz prikaz amplitude i faze[cite: 1].
    * **PSD (Power Spectral Density)**: Procena spektralne gustine snage za analizu šuma i harmonika[cite: 1].
* **Real-time vizuelizacija**: Pregledan prikaz signala na *Waveform Graph* indikatoru uz stalnu proveru statusa grešaka i bezbedno upravljanje sesijom[cite: 1].

## Tehnologije

* **Razvojno okruženje**: LabVIEW[cite: 1].
* **Hardver**: NI USB-5133[cite: 1].
* **Komunikacija**: NI-SCOPE drajveri[cite: 1].
