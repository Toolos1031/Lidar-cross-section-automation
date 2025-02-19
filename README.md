# Lidar-cross-section-automation
Automate the process of measuring trench geometry

## Overview

This project automates the process of analyzing and labeling LiDAR cross-sections. It processes .las files, extracts metadata, allows users to interactively select key points in 3D visualizations, and exports the results in .csv and .pkl formats.

### Features
* Automatic LiDAR cross-section loading from .las files.
* Interactive 3D visualization with Matplotlib.
* Point selection and labeling with real-time updates.
* Customizable controls (reset, skip, end, adjust point size).
* Photo preview support for reference images.
* Data export in .csv and .pkl formats.

### Instalation

1. Clone the repository
  ```sh
  git clone https://github.com/Toolos1031/Lidar-cross-section-automation.git
  cd Lidar-cross-section-automation
  ```
2. Install the required dependencies:
  ```sh
  pip install -r requirements.txt
  ```

### Usage
1) Run the script:
```sh
python Lidar-cross-section-automation.py
```
2) Select the required files and directories when prompted:
* Pickle file: Contains cross-section metadata.
* Scans directory: Folder with .las files.
* Photos directory: Folder with reference images.
  
3) Interact with the visualization:
* Click on points to select them.
* Use buttons for navigation and adjustments.
* Press n to move to the next section.
* Press <kbd>`</kbd> (backtick) to end the process.

4) The script will save the results in:
* csv.csv (inside the scans folder).
* Updated pickle file (with new selections).

### Controls & Interface

* 3D Visualization
  ![image](https://github.com/user-attachments/assets/ad16498c-77ab-4680-8191-a77473bdc697)
* Point Selection
  ![image](https://github.com/user-attachments/assets/dec2ef4d-56b1-4432-938d-637f3cacb7cb)
* Toolbar & Buttons
  ![image](https://github.com/user-attachments/assets/358b2faa-173c-4657-b3d3-4a3be9ef6ea5)
* Photo Preview
  ![image](https://github.com/user-attachments/assets/672fbb2c-1721-423e-9db2-cd22434dfdfd)


### Output Format

* CSV File
* Pickle file






