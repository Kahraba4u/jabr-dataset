# jabr-dataset

JabrDataset is the largest dataset of Arabic handwritten mathematical symbols. It is designed to support research and development in handwriting recognition, OCR, and machine learning for Arabic mathematics. The dataset provides a wide variety of handwritten samples, making it a valuable resource for academic studies, Al training, and educational technology

# 🧮 JabrDataset  


## 📝 Overview

**JabrDataset** is an extensive and valuable resource designed to support research and development in **handwriting recognition**, **Optical Character Recognition (OCR)**, and **machine learning** — specifically for **Arabic mathematics**.  
It is currently the **largest dataset of Arabic handwritten mathematical symbols**, providing a rich and diverse collection of samples.

---

##  Key Features and Collection Methodology

The dataset was meticulously collected from a wide variety of **handwritten notebooks** contributed by a diverse group of **students and teachers** across different **age groups**.  
This diversity ensures the dataset is **robust** and **reflective of real-world handwriting variations**.

The creation process involved several rigorous steps using **Python-based processing and segmentation** techniques:

1.  **Classification and Segmentation** – Each page was analyzed, classified, and segmented into individual **words** using custom Python scripts.  
2.  **Character Extraction** – Each word was further segmented into **individual character images**.  
3.  **Clustering and Noise Removal** – Segmented outputs were clustered to identify and remove **noise images** (e.g., stray marks, mis-segmented characters).  
4.  **Grouping and Sorting** – Similar character images were grouped, labeled, and moved into the **final dataset structure**, ensuring proper organization by **Arabic math symbol**.

---

##  Dataset Content and Scale

The **JabrDataset** currently contains:

-  **100,000+ images** of handwritten Arabic mathematical symbols  
-  **Arabic letters** used in mathematical contexts  
-  **Arabic-Indic numerals**  
-  **Mathematical functions and symbols**  

The dataset will continue to grow, expanding in **scale and diversity**, to better serve researchers and developers in the field of Arabic handwriting recognition.

---

## 💻 Target Applications

The dataset is ideal for:

-  **AI and Deep Learning** training for Arabic handwritten symbol recognition  
-  **Academic research** in OCR and handwriting recognition  
-  **Educational technology** projects, such as digital math input systems  

---

## 📁 Example Folder Structure

```bash
JabrDataset/
├── dataset_info.txt
├── README.md
├── ArabicLetters/
│   ├── alif/
│   │   ├── img_001.png
│   │   ├── img_002.png
│   │   └── ...
│   ├── ba/
│   │   ├── img_001.png
│   │   └── ...
│   └── ...
├── Numbers/
│   ├── ٠/
│   ├── ١/
│   ├── ٢/
│   └── ...
└── MathSymbols/
    ├── plus/
    ├── minus/
    ├── equal/
    └── ...

Tools and Technologies Used
Python – for preprocessing, segmentation, and clustering
OpenCV / PIL – for image handling and processing
NumPy / Pandas – for data organization and analysis

Citation
If you use this dataset in your research or project, please cite it as:
Hashedi, A. (2025). JabrDataset: The Largest Arabic Handwritten Mathematical Symbols Dataset.
GitHub Repository

License

This dataset is released under the MIT License
.
You are free to use, modify, and distribute it for research and educational purposes.

🌐 Links

🔗 GitHub Repository: https://github.com/Kahraba4u/jabr-dataset/

📫 Contact: your.email@example.com
