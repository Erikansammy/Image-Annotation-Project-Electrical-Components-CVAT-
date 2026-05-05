# Image-Annotation-Project-Electrical-Components-CVAT-
This project focuses on annotating electrical infrastructure images using CVAT, where insulators and surge arresters were accurately identified and labeled based on their type and material using bounding box annotations.
# 📌 Image Annotation Project – Electrical Components (CVAT)

## 📖 Overview

This project involves **image annotation and labeling** of electrical infrastructure components using the CVAT platform.

The objective was to accurately identify and label **insulators** and **surge arresters** based on their **type and material**, using bounding box annotations.

---

## 🎯 Project Objective

The goal of this task was to:

* Detect all visible electrical components in each image
* Draw precise bounding boxes around each object
* Classify each object into predefined categories
* Maintain high annotation accuracy and consistency

---

## 🛠️ Tools & Platform

* Annotation Tool: CVAT
* Annotation Type: Bounding Boxes
* Dataset: Electrical infrastructure images (provided)

---

## 🏷️ Label Classes

The annotation task strictly used **four predefined labels**:

1. **Insulator Polymer**
2. **Insulator Porcelain**
3. **Arrester Polymer**
4. **Arrester Porcelain**

No additional labels were created or modified.

---

## 📂 Task Access

* 🔗 **CVAT Task Link:https://app.cvat.ai/tasks/2002838/jobs/3589723
* 🖼️ **Sample Annotation Screenshot:<img width="1299" height="710" alt="image" src="https://github.com/user-attachments/assets/197a19b6-b413-4d7f-a452-251680f4e8fa" />







<img width="1309" height="711" alt="image" src="https://github.com/user-attachments/assets/ded0ffdf-884b-4e40-99fa-29821060d63c" />











<img width="1302" height="710" alt="image" src="https://github.com/user-attachments/assets/0bd15a7b-3524-4273-821e-98c697a78c31" />










<img width="1303" height="716" alt="image" src="https://github.com/user-attachments/assets/0760d820-b21c-4155-9bcb-a1b86e95fdb1" />










<img width="1305" height="714" alt="image" src="https://github.com/user-attachments/assets/12da1290-f83e-43cd-9e06-1aadeac4f3f5" />











<img width="1301" height="714" alt="image" src="https://github.com/user-attachments/assets/bd5d9c28-eb84-4517-953b-4d06d802dff0" />













<img width="1305" height="716" alt="image" src="https://github.com/user-attachments/assets/15705490-6c1f-4332-9543-0542235b5e94" />










---

## 🧩 Annotation Workflow

1. Logged into CVAT and created a new task
2. Uploaded all images for annotation
3. Carefully reviewed each image
4. Drew tight bounding boxes around each object
5. Assigned the correct label based on:

   * **Function** (Insulator vs Arrester)
   * **Material** (Polymer vs Porcelain)
6. Reviewed annotations for accuracy before submission

---

## 📏 Annotation Guidelines Followed

### ✔️ Bounding Box Rules

* Boxes tightly enclose each object
* Avoid unnecessary background inclusion
* No overlapping boxes unless required
* Each object has only **one box and one label**

### ✔️ Object Selection Rules

* Annotated all **clearly visible** objects
* Ignored:

  * Blurry objects
  * Severely occluded components
  * Broken or incomplete structures

---

## 🔍 Classification Criteria

### 1. Insulator Polymer

* Dark grey or black
* Rubber-like (composite material)
* Flexible sheds

### 2. Insulator Porcelain

* Light grey or off-white
* Glossy ceramic material
* Rigid structure

### 3. Arrester Polymer

* Dark rubber housing
* Typically connects phase to ground

### 4. Arrester Porcelain

* Light ceramic housing
* Heavier with segmented sheds

---

## ✅ Quality Assurance

To ensure high-quality annotations:

* Maintained **label consistency across all images**
* Verified **correct classification** before submission
* Ensured **tight and accurate bounding boxes**
* Followed all task rules strictly

---

## 📊 Outcome

* Successfully annotated all assigned images
* Maintained compliance with provided guidelines
* Delivered structured and high-quality labeled dataset

---

## 🚀 Notes

This project demonstrates practical experience in:

* Computer vision data annotation
* Object detection dataset preparation
* Using professional annotation tools like CVAT

---



