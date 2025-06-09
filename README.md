# AI-Powered Trust & Safety Platform
### Echo Innovators | HackOn with Amazon 

An early-stage prototype designed to enhance trust in e-commerce marketplaces like Amazon by detecting counterfeit listings, fake reviews, and seller manipulation using AI, computer vision, and LLMs.

---

# Overview

With 43% of top-selling products showing signs of review manipulation, e-commerce platforms face a growing trust crisis. Our project aims to solve this using a multi-layered AI approach:

- 🔎 Counterfeit detection via image anomaly analysis
- 📝 Semantic review analysis using LLMs
- 🧠 Seller credibility dashboard with Weekly Top Seller Badge
- ⏱️ Real-time product lifecycle fraud monitoring

This repository includes **frontend mockups** and **visual assets**. Backend logic, ML models, and data pipelines are currently in development for the prototype round.

---

## Feature Summary

| Feature                        | Status        | Description |
|-------------------------------|---------------|-------------|
| Seller Dashboard UI           | ✅ Completed  | Displays seller credibility score, return rates, badges |
| Product Page UI               | ✅ Completed  | Buyer-facing mockup showing trust score, fraud alerts |
| Fake Review Detection (LLMs)  | 🔜 In Progress| Planned semantic analysis using GPT/LLMs |
| Image Anomaly Detection (CV)  | 🔜 In Progress| Logo/text mismatch detection using OCR & Roboflow |
| Real-Time Lifecycle Tracking  | 🔜 Planned    | From listing to return – tracks suspicious behavior |
| Auto Refund & Review Cleanup  | 🔜 Planned    | For flagged products, supports user trust recovery |

---

## Tech Stack

#  Key Technologies 
#  Backend:Python

Flask/Django (for data processing & APIs)

#  ML Frameworks:
Hugging Face Transformers – for fine-tuning roberta-base on text classification.

Roboflow Inference SDK – for brand logo detection in images.

EasyOCR – for extracting text (brand names) from logo crops.

scikit-learn – for string similarity (with SequenceMatcher) and evaluation metrics (classification_report).

OpenCV (cv2) – for image processing (cropping logos, drawing bounding boxes).

# Database:
PostgreSQL / MongoDB (to store listings, reviews, seller info)

# Frontend:
React.js (Seller Dashboard, product pages, and alert popups)

---

##  Repository Structure

/Safety_platform-demo
├── .vscode/ → IDE config files
├── *.jpg / *.png → UI mockup assets
├── dashboard.css → Frontend styling (static)
├── README.md → You're here!


