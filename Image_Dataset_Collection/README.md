**📥 [Download the Dataset (Uploaded on Kaggle)](https://www.kaggle.com/datasets/onkarshinde02/divine-vision)**  


##  **Overview**  
DivineVision is a structured dataset designed to facilitate research and development in **image classification, deity recognition, and cultural heritage analysis**. It comprises **20 distinct categories**, each representing a deity, with **50 images per category**, sourced via **Bing Image Search**. The dataset is structured into labeled directories, ensuring ease of access and usability for machine learning and computer vision applications.  

### **Key Features:**  
- **20 deity categories** representing widely recognized gods and goddesses.  
- **50 high-resolution images per category**, curated for classification tasks.  
- **Comprehensive metadata** including image source, filename, and resolution.  
- **Labeled directory structure**, enabling seamless dataset integration.  

---

##  **Dataset Structure**  
```
DivineVision/
│── dataset_creator.ipynb  # Script for dataset generation
│── metadata.csv           # Image metadata (URL, filename, resolution)
│── god.txt                # List of deities and tier classification
│── dataset/               # Image dataset folder
│   ├── Ganesha/           # Category folder
│   │   ├── image1.jpg
│   │   ├── image2.jpg
│   │   └── ...
│   ├── Shiva/
│   ├── Vishnu/
│   ├── Lakshmi/
│   ├── ... (Other deities)
│
└── README.md              # Dataset documentation
```

---

##  **Metadata Information**  
The `metadata.csv` file provides essential details for each image:  

| **Column**    | **Description**                      |  
|--------------|--------------------------------------|  
| **Category**  | Name of the deity class             |  
| **URL**       | Source URL of the image            |  
| **Filename**  | Image filename in dataset          |  
| **Resolution**| Image dimensions (width x height)  |  

---

##  **Challenges & Considerations**  
Despite meticulous dataset curation, several challenges were encountered:  
- **Limited availability of deity-specific images**, leading to the inclusion of temple sculptures and artistic representations.  
- **Inconsistent naming conventions** across different sources.  
- **Diversity in artistic interpretations**, requiring careful categorization.  

All efforts have been made to ensure dataset quality and minimize noise while maintaining a balance across categories.  

---


##  **Potential Applications**  
The **DivineVision** dataset serves as a benchmark for various domains, including but not limited to:  
 **Automated deity recognition models**  
 **Cultural and religious studies**  
 **Computer vision-based art restoration**  
 **Image classification **  

---


