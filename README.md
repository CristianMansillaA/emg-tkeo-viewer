\# EMG Interactive Viewer with TKEO



This repository contains a Python script for interactive visualisation of

surface EMG signals, including rectified EMG and the Teager–Kaiser Energy

Operator (TKEO). The tool is intended for manual inspection of muscle

activation onsets and offsets.



The script was developed for research use and allows time-window navigation

and manual annotation using mouse and keyboard controls.



---



\## Features



\- Band-pass filtering of raw EMG signals

\- Rectified EMG visualisation

\- TKEO computation and display

\- Interactive time window navigation

\- Manual onset and offset marking using mouse clicks



---



\## Controls



\- \*\*Right mouse click\*\*: mark onset  

\- \*\*Left mouse click\*\*: mark offset  

\- \*\*Right arrow key\*\*: move time window forward  

\- \*\*Left arrow key\*\*: move time window backward  



---



\## Requirements



\- Python ≥ 3.9

\- numpy

\- pandas

\- scipy

\- matplotlib



Install dependencies with:



```bash

pip install numpy pandas scipy matplotlib



