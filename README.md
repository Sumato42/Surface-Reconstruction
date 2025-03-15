# 🎯 Curriculum-based Implicit Geometric Regularization for Learning Shapes

**Computer Vision | AI | Deep Learning | Shape Reconstruction**  

## 🔹 Overview
This project explores **Curriculum-Based Learning** in combination with **Implicit Geometric Regularization (IGR)** for learning 3D shapes.  

Our approach extends **DeepSDF** by:
1. **Introducing Implicit Geometric Regularization** to enhance shape learning.
2. **Applying Curriculum-Based Learning** to progressively refine representations.
3. **Initializing with a sphere** and incrementally learning more complex structures.

---

## 🚀 Key Features
- 🏗️ **Curriculum-Based Learning** - Gradual model refinement using a structured approach.
- 🔍 **Implicit Geometric Regularization** - Ensures smoother and more accurate shape learning.
- 🔄 **DeepSDF Extension** - Enhances the original **DeepSDF** framework with better shape priors.

---

## 🛠️ Methodology

The model follows a **three-phase learning strategy**:

1️⃣ **Initialization:**  
   - The model weights are set to approximate a sphere as the starting point.  

2️⃣ **Progressive Learning:**  
   - Using **Curriculum-Based Learning**, layers are gradually introduced to learn increasingly complex details.  

3️⃣ **Implicit Geometric Regularization:**  
   - A regularization term is applied to encourage smooth and realistic shape generation.  

---

## 📈 Results & Insights
### ✅ **Key Observations**
- **Faster Convergence:** Progressive layer introduction stabilizes training.
- **Improved Shape Quality:** IGR enhances smoothness and reduces artifacts.
- **Better Generalization:** The model adapts well to unseen 3D shapes.

### 📊 **Sample Results**
#### **1️⃣ Initial Sphere Approximation**
![Initial Sphere](assets/sphere.png)

#### **2️⃣ Progressive Refinement**
![Shape Learning Progress](assets/progressive_learning.png)

#### **3️⃣ Final Shape Output**
![Final Shape](assets/final_shape.png)

---

## 📚 Related Work
- 🔹 **[DeepSDF: Learning Continuous Signed Distance Functions for Shape Representation](https://arxiv.org/abs/1901.05103)**
- 🔹 **[Implicit Geometric Regularization for Learning Shapes](https://arxiv.org/abs/2101.06849)**

---

## 📦 Installation & Usage
🔒 **Due to confidentiality, the full code is not publicly available.
Please email me if you wish to learn more about Curriculum-IGR** 
