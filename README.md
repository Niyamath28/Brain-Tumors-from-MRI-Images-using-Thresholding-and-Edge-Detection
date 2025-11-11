# 🧠 Detection of Brain Tumors from MRI Images using Thresholding and Edge Detection

## 📘 Project Description
This project aims to detect **brain tumors** from **MRI images** using basic **image processing techniques** such as **thresholding** and **edge detection**.  
The main objective is to automatically highlight tumor regions for early diagnosis and visualization — without using complex machine learning models.

---

## ⚙️ Methodology

1. **Input MRI Image:**  
   Load an MRI brain scan image.

2. **Preprocessing:**  
   - Convert the image to **grayscale**  
   - Apply **Gaussian blur** to remove noise

3. **Thresholding:**  
   - Apply **Otsu’s Thresholding** to separate the tumor region from the background  
   - Converts grayscale image into binary (black and white)

4. **Edge Detection:**  
   - Use **Canny Edge Detection** to find the edges or boundaries of the tumor region

5. **Output:**  
   - Display the original MRI image  
   - Show the thresholded and edge-detected tumor region

---

## 🧩 Folder Structure

```
Brain_Tumor_Detection/
│
├── Code/
│   ├── Final_Brain_Tumor.n       # Main Python program
│   ├── ranisodiff_function.m            
│
├── Data/
│   ├── m1.jpg
│   ├── m2.jpg
│   └── m3.jpg
│
└── README.md
```

---

## 💻 Requirements

- Python 3.x  
- OpenCV  
- NumPy  
- Matplotlib  

Install all dependencies:
```
pip install -r requirements.txt
```

---

## ▶️ How to Run

1. Place your MRI images in the `Data/` folder.  
2. Run the program:
   ```
   python Code/brain_tumor_detection.py
   ```
3. The program will display:
   - Original MRI image  
   - Thresholded image  
   - Edge-detected image showing tumor outline

---

## 📊 Expected Output
- The tumor region appears **highlighted or outlined** after thresholding and edge detection.  
- You can visualize the tumor area for better diagnosis support.

---

## 📚 Applications
- Medical image analysis  
- Brain tumor diagnosis assistance  
- Research in biomedical image processing  

