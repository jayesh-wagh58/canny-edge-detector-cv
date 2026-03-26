This project is a Python-based tool designed to automate the process of edge detection in digital images. Using the OpenCV library, it applies a Gaussian Blur for noise reduction and the Canny Edge Detection algorithm to extract structural boundaries from images in bulk.

## 🚀 Features
- **Batch Processing**: Automatically processes all images in a folder.
- **Noise Reduction**: Integrated Gaussian filtering to improve edge accuracy.
- **Portability**: Uses relative pathing for easy execution across different environments.
- **Clean Output**: Separates source images from processed results.

---

## 🛠️ Installation & Setup

### 1. Prerequisites
Ensure you have Python 3.x installed on your system. You can check this by running:

```bash
python --version
```

### 2. Clone the Repository

```bash
git clone https://github.com/jayesh-wagh58/canny-edge-detector-cv.git
```
### 3. Navigate to Repository
```bash
cd canny-edge-detector-cv
```
### 4. Install Dependencies

This project requires the `opencv-python` library. Install it using pip:
```bash
pip install opencv-python
```

---

## 📁 Project Structure
```text
.
├── input/                # Place your source images here (.jpg, .png, .webp)
├── output/               # Processed edge-detected images will appear here
├── canny_edge_detector.py # The main Python script
├── README.md             # Project documentation
└── requirements.txt      # List of dependencies
```

---

## 💻 How to Run

1. **Prepare Images**: Place the images you want to process inside the `input` folder.
   
      If you want to see the folders visually to "attach" (paste) your images, type:
  ```bash
   explorer .
   ```
2. **Execute the Script**: Run the following command in your terminal/command prompt:
  ```bash
   python canny_edge_detector.py ab
   ```
3. **View Results**: Once the script finishes, open the `output` folder to see the generated edge-maps.

---

## ⚙️ Technical Configuration
The script is pre-configured with the following parameters for optimal results:
- **Gaussian Blur**: (5, 5) Kernel
- **Low Threshold**: 50
- **High Threshold**: 150

To change these values, edit the `canny_edge_detection` function call in `canny_edge_detector.py`.

---

## 👤 Author
- **Name**: Jayesh Wagh
- **Platform**: VITyarthi BYOP Submission
