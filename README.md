```markdown
# 🧫 BactoVision

**BactoVision** is an AI-powered Clinical Decision Support System (CDSS) designed to automate bacterial colony counting and Antimicrobial Susceptibility Testing (AST) measurements from agar plate images.

The application combines state-of-the-art deep learning with image processing techniques to provide fast, accurate, and reproducible microbiological analysis.

---

## Features

- 🔬 Automated bacterial colony detection
- 🧫 Colony counting using YOLOv8
- 📏 Automatic AST inhibition zone measurement
- 📊 Interactive Streamlit interface
- 📈 Export results to CSV
- 🖼️ Image visualization and annotation
- ⚡ Fast inference suitable for laboratory workflows

---

## Technologies Used

- Python
- Streamlit
- Ultralytics YOLOv8
- OpenCV
- NumPy
- Pandas
- Pillow
- Matplotlib

---

## Project Structure

```

BactoVision/
│
├── appfinal.py
├── CFU_counter.py
├── AST_measurements.py
├── gallery.py
├── gatekeeper.py
├── requirements.txt
├── README.md
├── logo_white2.png
└── ...

````

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/BactoVision.git
cd BactoVision
````

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## Run the Application

```bash
streamlit run appfinal.py
```

---

## Application Modules

* Colony Detection
* Colony Counting
* AST Measurement
* Result Visualization
* Report Export

---

## AI Model

The project utilizes **YOLOv8** for bacterial colony detection and combines traditional computer vision techniques for automated AST inhibition zone measurements.

---

## Future Improvements

* Multi-species support
* Cloud deployment
* Database integration
* Laboratory Information Management System (LIMS) integration
* Explainable AI visualization

---

## License

This project is intended for educational and research purposes.

---

## Author

**Yousef Abdel Haseeb**

Faculty of Scinsce, Capital Uinversty (Helwan Universty), Egypt

Graduation Project — BactoVision

```
```
