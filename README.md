# Face Recognition App using Streamlit  
This is a face recognition application built using **Python, Face-Recognition API, and Streamlit framework**. The app allows users to **upload an image containing faces and perform face recognition** using the `face_recognition` library.

---

## **✨ Features**  
✅ Face detection and recognition  
✅ Multi-face recognition  
✅ Option to display recognized faces  
✅ User-friendly interface  

---

## **🛠 Requirements**  
- Python 3.9  
- Streamlit 1.22.0  
- face_recognition  

---

## **📂 Repository Structure**  
├── dataset
│ ├── ID_Name.jpg
│ ├── ...
│
├── pages
│ ├── 1_🔧_Updating.py
│ ├── 2_💾_Database.py
│
├── Tracking.py
├── utils.py
├── config.yaml
├── requirements.txt
├── packages.txt
└── README.md

---

## **📌 Description**  
- `dataset/` → Contains images of people to be recognized. The file name format is `ID_Name.jpg` (e.g., `1_Elon_Musk.jpg`, `2_Jenna_Ortega.jpg`).  
- `pages/` → Contains individual pages of the app. Additional pages can be added using the format `Order_Icon_PageName.py`.  
- `Tracking.py` → The home page of the app, used for tracking in real-time via webcam or images.  
- `utils.py` → Contains helper functions used by the app.  
- `config.yaml` → Stores configuration settings such as dataset directory paths and prompt messages.  
- `requirements.txt` → Lists dependencies required to run the app.  
- `packages.txt` → Lists packages needed for deployment on **Streamlit Cloud**.  

---

## **🚀 Installation & Setup**  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/FACE-RECOGNITION-APP.git
cd FACE-RECOGNITION-APP
### **2️⃣ Install the Dependencies **  
```bash
pip install -r requirements.txt
### **3️⃣ Run the Application**  
```bash
streamlit run Tracking.py
## 🔍 Usage
✅ Real-time Tracking using Webcam
✅ Tracking Faces in Image Files
✅ Updating Database (Add, Delete, Update Faces)
✅ Viewing the Face Database






