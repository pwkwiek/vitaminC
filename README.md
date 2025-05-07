## Histogram Matching Techniques for Enhanced Vitamin C Prediction in Neural Networks
*C-ing is Believing: Predicting Vitamin C concentration with Deep Learning*

## 🧪 Prediction of Vitamin C Concentration – Vol. 2

This repository presents an improved neural network model for predicting vitamin C concentration from images of chemical solutions. The work builds on earlier efforts (Vol. 1) to assess the **influence of image color standardization** on regression performance in deep learning models.

### 🔬 Vol. 2 Highlights:

* Enhanced model architecture yielding **higher R² values** and **lower MSE** than the previous version.
* The final neural network implementation can be found in [`example_of_final_net.ipynb`](./example_of_final_net.ipynb).
* The results validate the significant role of standardized imaging in improving prediction accuracy.

---

## 📸 Background – Vol. 1 Summary

The initial study proposed a **template-based histogram matching method** for color standardization. A custom color chart was developed through a series of digital imaging experiments. Photographs of solutions were captured under **natural and artificial lighting** to evaluate robustness.

### Key Findings from Vol. 1:

* **MSE** for the test set dropped to **2.92–7.96 µg/mL** (standardized) vs **15.61–34.13 µg/mL** (non-standardized).
* **R² values** reached approximately **0.99** for standardized images.
* The approach helped **mitigate light reflection artifacts**, a common issue in imaging liquid samples.

---

## 📄 Related Publication

Final results and methodology are detailed in the article:

  **"Color standardization of chemical solution images using template-based histogram matching in deep learning regression"**
  🖋 Patrycja Kwiek, Małgorzata Jakubowska
  📚 *Algorithms*, 2024, Vol. 17, Issue 8, Article No. 335, pp. 1–22
  🔗 ISSN: 1999-4893
