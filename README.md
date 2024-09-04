
# VolumeRenderer DICOM-VTK

## Overview
This project is a volume renderer for DICOM files, built using VTK and Qt. It supports both surface rendering and ray casting rendering techniques. The application allows users to load DICOM files and adjust the iso value during surface rendering.

## Features
- **Load DICOM File:** Load and visualize DICOM files in the application.
- **Surface Rendering:** Render the surface of the 3D model with an adjustable iso value.

  https://github.com/user-attachments/assets/8ebe997f-4eae-441e-86d6-867701c8efd6
  
- **Ray Casting Rendering:** Render the 3D model using ray casting techniques.

  https://github.com/user-attachments/assets/98d81c1f-75dc-4256-a09b-f811b2396f9e

## Installation

### Prerequisites
- **Qt:** Install Qt to design and develop the GUI.
- **VTK (Visualization Toolkit):** Install VTK for handling DICOM files and rendering.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/RanaHany10/VolumeRenderer-DICOM-VTK.git
   ```
2. Install the necessary dependencies:
   - Install Qt (You can download it from [Qt Downloads](https://www.qt.io/download))
   - Install VTK (Refer to the [VTK Documentation](https://vtk.org/documentation/))

3. Open the project in your preferred IDE (e.g., VS code).

4. Build and run the project.

## Usage
- **Load DICOM File:** Click on the "Load File" button to select and load a DICOM file.
- **Choose Rendering Technique:** Select either surface rendering or ray casting rendering.
- **Adjust Iso Value (for Surface Rendering):** Use the slider to adjust the iso value and observe the changes in real-time.

## Interface Design
The user interface is designed using the Qt Designer. It enables users to:
- Load DICOM files.
- Choose the rendering technique.
- Adjust the iso value in the case of surface rendering.


