# Document Scanner using OpenCV

## Overview
This project is a document scanner implemented using OpenCV, allowing users to connect an IP camera wirelessly and scan documents.

## Features
- Document scanning using an IP camera
- Automatic document detection and perspective correction
- Image saving in various formats (e.g., PDF, JPEG)

## Setup
1. **Install Dependencies**:
   - Make sure you have Python installed on your system.
   - Install OpenCV and any other required libraries using pip:
     ```
     pip install opencv-python
     ```

2. **Clone Repository**:
   - Clone this repository to your local machine:
     ```
     git clone <repository_url>
     ```

3. **Connect IP Camera**:
   - Install IP Camera available on Playstore
   - Make sure your IP camera is connected to the same network as your computer.
   - Obtain the IP address of your camera.

4. **Run the Program**:
   - Navigate to the project directory.
   - Run the main Python script:
     ```
     python document_scanner.py --ip <camera_ip_address>
     ```

5. **Scan Documents**:
   - Once the program is running, point the IP camera towards the document you want to scan.
   - Adjust the camera position and angle if needed.
   - Press the specified key (e.g., 'S') to capture and scan the document.

## Usage
- Upon successful scanning, the program will display the scanned document with perspective correction applied.
- Press the specified key (e.g., 'Q') to quit the program.
- The scanned document will be saved automatically in the specified directory.

