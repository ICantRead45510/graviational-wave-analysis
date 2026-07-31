## Setup & Dependency Challenges

> During tutorials, had problems with the suggested versions of numpy and similar libraries being outdated compared to the current versions, requiring a lot of time to figure out which imports worked and finding alternative versions for those that didn’t.

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
