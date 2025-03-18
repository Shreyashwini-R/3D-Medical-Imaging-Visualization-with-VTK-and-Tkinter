# 3D-Medical-Imaging-Visualization-with-VTK-and-Tkinter
## 📖 Overview
This project is a 3D Medical Imaging Visualization Tool built using VTK (Visualization Toolkit) and Tkinter. It allows users to visualize and interact with 3D medical imaging data, such as CT scans, using the Marching Cubes algorithm. The tool provides a graphical user interface (GUI) to toggle the visibility of different anatomical structures (e.g., muscle, brain, skull) extracted from the DICOM dataset.

The application is designed for medical professionals, researchers, and students to explore and analyze 3D medical imaging data in an interactive and user-friendly manner.
## 🚀 Features
### 1. DICOM Image Loading
- Load and visualize DICOM image datasets (e.g., CT scans).

- Supports multi-slice DICOM data for 3D reconstruction.
### 2. Marching Cubes Algorithm
- Extracts 3D surfaces from volumetric data using iso-values.

- Allows customization of iso-values for different anatomical structures. 
### 3. Interactive 3D Visualization
- Visualize 3D models of anatomical structures (e.g., muscle, brain, skull).

- Rotate, zoom, and pan the 3D model for better exploration.
### 4. Structure Visibility Toggle
- Toggle the visibility of specific structures (e.g., skull, muscle, brain) using a Tkinter GUI.

- Option to show or hide all structures simultaneously.
### 5. Color-Coded Structures
Assigns distinct colors to different anatomical structures for easy identification.

## Technologies Used
- **VTK (Visualization Toolkit):** For 3D rendering and visualization.

- **Tkinter:** For creating the graphical user interface (GUI).

- **DICOM Image Reader:** For loading and processing DICOM datasets.

- **Marching Cubes Algorithm:** For extracting 3D surfaces from volumetric data.

## 🔧 Installation
Prerequisites
- **Python 3.8+:** Ensure Python is installed on your system.

- **VTK:** Install VTK using pip.

- **Tkinter:** Pre-installed with Python (no additional installation required).
  ### Steps to Run the Application
  #### 1.Clone the Repository:
  ```git clone https://github.com/your-username/3D-Medical-Imaging-Visualization-with-VTK-and-Tkinter.git ```
  ```cd 3D-Medical-Imaging-Visualization-with-VTK-and-Tkinter```
  #### 2.Install Dependencies:
  ```pip install vtk```
  #### 3.Prepare DICOM Data:
  - Place your DICOM dataset in a folder (e.g., ct/).

  - Update the dicom_dir variable in the code with the path to your DICOM folder.
  #### 4.Run the Application:
  ```python 2D_to_3D.py ```
  #### 5.Interact with the Application:
  - Use the Tkinter buttons to toggle the visibility of anatomical structures.

  - Interact with the 3D model using your mouse (rotate, zoom, pan).
 
## Usage
#### 1. Load DICOM Data
- Place your DICOM dataset in the specified folder (ct/ by default).

- The application will automatically load and process the data.
#### 2. Visualize 3D Structures
- The application will render 3D models of anatomical structures (e.g., muscle, brain, skull) using the Marching Cubes algorithm.
#### 3. Toggle Structure Visibility
- Use the Tkinter GUI to toggle the visibility of specific structures:

    - Show Skull: Toggle skull visibility.

    - Show Muscle: Toggle muscle visibility.

    - Show Brain: Toggle brain visibility.

    - Show All: Show all structures simultaneously.
#### 4. Interact with the 3D Model
- **Rotate:** Click and drag the mouse.

- **Zoom:** Scroll up or down.

- **Pan:** Hold Shift and drag the mouse.

## Future Enhancements
- **Support for Other Medical Imaging Formats:** Add support for NIfTI, NRRD, and other formats.

- **Advanced Segmentation:** Integrate machine learning models for automated segmentation of anatomical structures.

- **Volume Rendering:** Add volume rendering capabilities for better visualization of soft tissues.

- **Export 3D Models:** Allow users to export 3D models in STL or OBJ formats.
## Contributing
Contributions are welcome! Please follow these steps:

- **Fork the repository.**

- **Create a new branch**
```git checkout -b feature/YourFeatureName```

- **Commit your changes**
```git commit -m 'Add some feature```

- **Push to the branch**
```git push origin feature/YourFeatureName```

- **Open a pull request**

## Contact
For any queries or feedback, feel free to reach out:

- **Name:** Shreyashwini R

- **Email:** Shreyashwinir@gmail.com

- **GitHub:** Shreyashwini-R



