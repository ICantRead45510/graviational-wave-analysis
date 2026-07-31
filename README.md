## Key Takeaways & What I Learned

Through this project, I gained hands-on experience in gravitational wave astrophysics and signal processing:
* **Digital Signal Processing:** Learned how to apply bandpass ($30\text{--}400\text{ Hz}$) and notch filtering ($60\text{ Hz}$) to isolate subtle signals buried under seismic noise and power line interference.
* **Time-Frequency Analysis:** Understood why standard time-domain plots aren't always enough and how **Q-transforms** dynamically map frequency evolution over time to expose chirp signatures.
* **Multi-Detector Verification:** Saw firsthand how cross-referencing strain data across independent sites (LIGO Hanford and LIGO Livingston) validates real cosmic events vs. localized instrumental glitches.
* **Python Environment Troubleshooting:** Resolved modern Python 3.12 library dependency and version mismatch issues when working with legacy open-data workshop tutorials.

---
## Project Overview

This project examines the first occurrence of a recorded gravitational wave from a black hole merger from the LIGO Hanford and LIGO Livingston observatories on September 14, 2015. 

Raw detector strain data was conditioned to suppress low frequency noise and power hum using open strain data from the **Gravitational Wave Open Science Center**, also using python packages:
* `gwpy`
* `pycbc`
* `matplotlib`

A **Q-transform time-frequency spectrogram** was plotted, making a visible “chirp” signal where the black hole merger was isolated.

<img width="1048" height="559" alt="HANFORD SPECTROGRAM" src="https://github.com/user-attachments/assets/b60f95c1-fd1a-4be5-90eb-7252bd9266ff" />
<img width="1048" height="559" alt="LIVINGSTON SPECTROGRAM" src="https://github.com/user-attachments/assets/cacf8b2f-66ee-4b57-88c1-98247a068beb" />
