# XAI Laboratory

## Dataset Structure

```
Base Folder/
├── class1/
├── class2/
└── ...
```

## Tasks

1. Case study on real-world use cases where ML models went badly wrong (No SMOTE)

2. Perform Exploratory Data Analysis on:

   * Structured data (.csv)
   * Unstructured data (text)
   * Image data

3. Post-hoc analysis visualizations:

   * Partial Dependence Plot (PDP)
   * CNN (custom model):

     * Layer-wise Relevance Propagation (LRP) – image provided
     * Gradient CAM – image dataset and test image provided
     * Saliency Map – image dataset and test image provided
     * Surrogate Explainer – structured data (.csv)

4. Feature importance and sensitivity analysis – structured data (.csv)

5. Interpretability using LIME:

   * Tabular (.csv)
   * Image (custom CNN, image dataset and test image provided)
   * Text (.csv or .txt)

6. SHAP on ML and DL models – local and global explanations

7. Human-friendly explanations with TCAV:

   * Image (custom CNN, concept and actual images provided)
   * Text (Logistic Regression with TF-IDF, using concept words)
