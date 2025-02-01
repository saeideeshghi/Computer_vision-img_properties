# Advanced Image Processing 🚀

A desktop application for advanced image processing built with Python, Tkinter, OpenCV, and Matplotlib. This tool provides various functionalities such as brightness/contrast adjustment, color model manipulations (RGB, HSV, LAB, etc.), filters (Gaussian, Median, Canny, Sharpen, Sepia, Emboss, Histogram Equalization, Thresholding), image rotation, and flipping. The user interface supports both English and Persian languages.

## ✨ Key Features
- **Multilingual UI:** Switch between English and Persian seamlessly.
- **Color Model Adjustments:** Modify images in various color spaces (RGB, HSV, LAB, YCbCr, HSL, XYZ, Grayscale, CMYK).
- **Advanced Filters:** Apply multiple filters including Gaussian Blur, Median Blur, Canny Edge, Sharpen, Sepia, Emboss, Histogram Equalization, and Thresholding.
- **Image Transformations:** Rotate images by 90°, 180°, 270° and perform horizontal/vertical flipping.
- **Histogram Display:** Visualize the histogram of the processed image using Matplotlib.
- **User-Friendly Interface:** Built with Tkinter and styled with ttk for a modern look.

## 🛠 Installation & Setup

### Prerequisites
- Python 3.8+
- Tkinter (usually included with Python)
- A working GPU is optional (for OpenCV operations, CPU is sufficient)

### Required Libraries

Create a file named `requirements.txt` with the following content:

```
Pillow
opencv-python
numpy
matplotlib
```
Then install the dependencies via pip:
```
pip install -r requirements.txt
```
▶️ Running the Application
Simply run the main Python script:

```
python Main.py
```
📂 Project Structure

```
.
├── main.py                # Main application script (contains the AdvancedImageProcessor class)
├── requirements.txt       # List of required libraries
└── README.md              # Project documentation (this file)
```

🔗 References

- Tkinter Documentation: https://docs.python.org/3/library/tkinter.html
- OpenCV Documentation: https://docs.opencv.org/
- Pillow Documentation: https://pillow.readthedocs.io/
- Matplotlib Documentation: https://matplotlib.org/

🤝 Contributing
Contributions are very welcome! To contribute:

- 1.Fork the repository.
- 2.Create a new branch (e.g., git checkout -b feature/YourFeature).
- 3.Commit your changes (e.g., git commit -m 'Add Your Feature').
- 4.Push to your branch (git push origin feature/YourFeature).
- 5.Open a Pull Request.

📜 License
This project is licensed under the MIT License.

Let's process images smarter and have fun! ⚡
