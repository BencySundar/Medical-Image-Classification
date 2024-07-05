# Skin Lesion Classification for Early Detection of Skin Cancer

Skin cancer can be effectively treated with early detection. One of the challenges faced by dermatologists is accurately differentiating between various types of skin lesions visually. Machine learning-based automated classification systems can assist dermatologists in diagnosing skin lesions with greater precision and speed.

## Problem Statement

This project aims to build a machine-learning model to classify seven types of skin lesions based on images:

- Melanocytic nevi
- Melanoma
- Benign keratosis-like lesions
- Basal cell carcinoma
- Actinic keratoses
- Vascular lesions
- Dermatofibroma

## Benefits

- Early detection of skin cancer.
- Enhanced accuracy in skin lesion classification.
- Increased accessibility for dermatologists.
- Reduction in wait time and biopsy costs.

## Dataset

### Iterations:

| Iteration | Model Description                                | Accuracy | Precision | Recall | F1-Score |
|-----------|--------------------------------------------------|----------|-----------|--------|----------|
| 1         | Baseline SVM model                               | 69%      | 0.66      | 0.69   | 0.66     |
| 2         | CNN model without addressing class imbalance      | 68%      | 0.58      | 0.68   | 0.61     |
| 3         | CNN model with SMOTE for class imbalance handling | 70%      | 0.68      | 0.70   | 0.69     |
| 4         | CNN model with SMOTE and data augmentation        | 51%      | 0.70      | 0.51   | 0.56     |
| 5         | Transfer learning                                | 64%      | 0.74      | 0.64   | 0.68     |

### Conclusion

The CNN model incorporating SMOTE to handle class imbalance shows promise in detecting various types of pigmented skin lesions. Compared to the accuracy and recall rates reported for dermatologists in previous studies, the CNN model achieved higher accuracy and recall, indicating its potential to assist clinicians in faster and more accurate lesion detection.

## References

- [National Library of Medicine study on dermatologist accuracy](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7519424/)

