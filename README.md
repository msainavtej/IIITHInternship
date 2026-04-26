# Week 4 Task 2 – YOLO Dataset Creation

## 📌 Task Overview
Created a custom labeled dataset for **People Detection** using YOLO format.

---

## 🎥 Data Source
- Video sourced from Intel sample videos repository
- Frames extracted using FFmpeg (10 FPS)

---

## 🛠️ Steps Performed
1. Extracted frames from video (~600 images)
2. Split dataset:
   - Train: 100 images
   - Validation: 39 images
   - Test: remaining images
3. Labeled images using Label Studio (bounding boxes)
4. Exported annotations in YOLO format
5. Cleaned dataset:
   - Fixed filename mismatches
   - Removed images without labels
6. Created YAML configuration file
7. Generated train.txt and val.txt

---

## 📂 Dataset Structure
- labels/train → training labels
- labels/val → validation labels
- dataset.yaml → configuration file
- train.txt, val.txt → image paths

---

## 🧠 Class Details
- 0 → person

---

## ⚠️ Notes
- Dataset was manually verified for consistency
- All images have corresponding label files

---

## 🚀 Outcome
Successfully created a YOLO-ready dataset suitable for training an object detection model.
