# 🧠⚔️ CLASSIFICATION COMPARISON QUEST - MAIN QUEST

> *“Balance the data. Sharpen the model. Farm insight, not just accuracy.”*

---

## 🗺️ Quest Overview

This repository contains a **classification comparison experiment** developed for COS711 Assignment 3. The quest explores how **model choice and enhancement strategies** affect classification performance, with a focus on understanding *why* improvements succeed or fail.

Two main builds are explored:

* ⚔️ A **baseline classifier**
* 🚀 An **enhanced classifier** (ResNet-based)

Rather than chasing raw scores, the quest focuses on **diagnosing weaknesses**, **learning from failed upgrades**, and identifying **clear evolution paths**.

---

## 📁 Quest Inventory

```
.
├── COS711_A3.ipynb              # Baseline classification build
├── Assignment3_Resnet.ipynb     # Enhanced (ResNet) build
├── README_COS711_A3.md          # Quest log
```

---

## ⚙️ Gear Equipped — Tech Stack

* **Python 3**
* **NumPy & Pandas** — data handling
* **Matplotlib / Seaborn** — visual diagnostics
* **Scikit-learn** — evaluation metrics
* **PyTorch / Torchvision** — deep learning models

---

## 📊 Data Preparation — World Setup

* Dataset loaded and split into **train / validation / test** sets
* Labels provided for supervised learning

Basic preprocessing was applied to enable model training and evaluation.

---

## 🧠 Experimental Setup — Strategy Phase

### 🧩 Builds Compared

* **Baseline Model**

  * Simple classifier used as a reference point

* **Enhanced Model**

  * Deeper architecture using **ResNet**
  * Intended to improve feature extraction and generalization

Both builds use the same dataset splits and evaluation metrics to ensure a fair comparison.

---

## 🏟️ Classification Results — Battle Arena

Evaluation focuses on:

* Overall accuracy
* Confusion matrices
* Qualitative inspection of class-wise behaviour

The enhanced model shows **only marginal improvement**, highlighting that architectural upgrades alone are not always sufficient.

---

## 🚀 Classification Enhancement — Power-Ups

Enhancement attempts focused on:

* Increasing model depth
* Leveraging pretrained-style architectural ideas (ResNet)

While improvements were observed, gains were **limited**, suggesting bottlenecks outside the model architecture itself.

---

## 🚧 Known Weaknesses & Side Quests

The main quest is complete, but several **side quests** remain to unlock the build’s full potential.

### 🧩 Side Quest 1: Data Insight & Class Balance

* Limited **Exploratory Data Analysis (EDA)**
* Class imbalance not explicitly addressed

**Why it matters:**

* Models may optimize for majority classes
* Overall accuracy can mask poor minority-class performance

---

### 📉 Side Quest 2: Mediocre Performance Ceiling

* Classification results plateau early
* Marginal gains from architectural enhancement

**Why it matters:**

* Indicates data-level or loss-function-level limitations

---

### 🔍 Side Quest 3: Result Interpretability

* Confusion matrices presented in text form
* Hard to visually diagnose class-wise errors

**Why it matters:**

* Visual diagnostics speed up failure analysis

---

## 🛠️ Future Upgrades (Patch Notes — v1.1)

Planned upgrades for the next iteration:

* Add **explicit EDA** (class distributions, samples per class)
* Apply **class imbalance handling**:

  * Class-weighted loss
  * Oversampling / data augmentation
* Replace text confusion matrices with **heatmap visualizations**
* Tune hyperparameters (learning rate, batch size, epochs)

These upgrades target **root causes**, not just surface-level performance.

---

## 🏁 Quest Status

🧩 **Main Quest:** Classification Comparison
🎯 **Objective:** Understand performance bottlenecks
🚀 **Outcome:** Functional comparison with clear evolution paths

---

## 👤 Player Profile

**Wadalisa Oratile Molokwe**
Honours Student | Network Engineer & System Administrator

---

*GitHub quest log — built for learning, reflection, and long-term evolution.*
