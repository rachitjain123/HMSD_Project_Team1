# Hydrological Modelling and Software Development
# TEAM - 1
An implementation of the Hydrological models

![ScreenShot of Project](project_cover.png)

## Presentation Link (Prezi)
https://prezi.com/view/7w5M4i9wDnDnqo5w0IhU/?fbclid=IwAR1cIW13hLYPScTNK-j8cOxUbYKo26UoKyyRH-UJ8_268Kui_z5e2lhaAsQ

## Structure

- _main.py - Contains the main code to run the GUI application
- HMSDWorkDistribution.pdf - Work Distribution of Team members
- Description.pdf - Description of the Project
- flowchart.pdf - Flow of the project
- Shp file for a basin
- rainfall-prediction.xls - Predict future data using time-series ARIMA
- Discharge_location, basin_mat

## Pre-requisites

Below are the pre-requisites to be satisfied before the package can be used.

- Make sure `python3` is installed.
- Package requirements:
  - `matlab.engine`
  - `matplotlib` 
  - `glob`
  - `tkinter` 
  - `pandas` 
  - `numpy`
  - `cv2`
  - `scipy.io`
  - `tkinter.ttk`
  - `tkinter.filedialog`
  - `matplotlib.backends.backend_tkagg`
  - `matplotlib.backend_bases`
  - `matplotlib.pyplot`
  - `matplotlib.figure`
  - `tkdocviewer`
  - `sklearn.ensemble`
  - `seaborn`
  - `datetime`

- If the above packages are not installed,

  - You need to install the packages
  - requirements file is also present

## Usage

- Once the pre-requisites are satisfied, the [demo](main.py) can be run by running the following command:

  ```bash
  python3 main.py
  ```
