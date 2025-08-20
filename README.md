# 🌄 Panorama Stitching Pro  

[![License](https://img.shields.io/github/license/anthonylucky1909/Panorama-Stitching-Pro.svg)](LICENSE)  
[![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python&logoColor=white)](https://www.python.org/)  
[![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?logo=opencv)](https://opencv.org/)  
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)  

---

## 🧐 Overview  

**Panorama Stitching Pro** creates seamless panoramas by aligning and merging multiple images.  
It leverages **SIFT-based feature detection**, **homography estimation**, and **multi-band blending** for high-quality results.  

✨ Core pipeline:  
- 🔍 **Feature Detection (SIFT)**  
- 🔗 **Feature Matching & Alignment**  
- 🌐 **Homography Estimation**  
- 🔄 **Seamless Image Blending**  

<details>
<summary>📸 Example Outputs</summary>

**Feature Matching**  
![Matching Result](matching_result/local_window/data3.jpg)  

**SIFT Keypoints**  
![SIFT Keypoints](matching_result/sift/data3.jpg)  

**Final Panorama**  
![Final Result](result/sift/data3.jpg)  

</details>

---

## ⚙️ Setup & Run  

1. **Clone the repo**  
   ```bash
   git clone https://github.com/anthonylucky1909/Panorama-Stitching-Pro.git
   cd Panorama-Stitching-Pro
   ```

2. **Set up environment** (choose one)  
   ```bash
   conda env create -f envs.yml
   conda activate panorama_env
   ```
   or  
   ```bash
   pip install -r requirements.txt
   ```

3. **Run notebooks**  
   ```bash
   jupyter notebook
   ```
   Open `main.ipynb` or `Panorama_Stitching.ipynb` to execute the pipeline.  

4. **View results** in the `result/` folder.  

---

## 📚 References  

- 📖 [SIFT Paper (Lowe, 2004)](https://www.cs.ubc.ca/~lowe/papers/ijcv04.pdf)  
- 📖 OpenCV Documentation – [Feature Detection & Description](https://docs.opencv.org/master/db/d27/tutorial_py_table_of_contents_feature2d.html)  
- Detailed methodology: see [`pdf_report.pdf`](pdf_report.pdf)  

---
