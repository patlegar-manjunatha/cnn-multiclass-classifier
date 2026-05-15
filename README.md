# CNN Multiclass Classification

A simple CNN-based image classification project built from scratch.

The project focuses on building a stable and lightweight CNN pipeline without using pretrained models.

---

## Features

- Custom CNN architecture
- Multiclass image classification
- Saved trained models
- Clean and minimal project structure

---

## Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Streamlit
- OpenCV
- Matplotlib

---

## Project Structure

```bash
.
├── models/
│   └── cnn_model.keras
├── notebooks/
│   └── experimentation.ipynb
├── requirements.txt
├── README.md
└── LICENSE
````

---

## Approach

1. Load and preprocess image dataset
2. Build CNN architecture from scratch
3. Train the model using training data
4. Evaluate on test dataset
5. Save trained model inside `models/`


The architecture was intentionally kept simple and efficient according to the task constraints.

---

## Model Details

* CNN built completely from scratch
* No pretrained models used
* Includes:

  * Conv2D layers
  * Batch Normalization
  * MaxPooling
  * Dense layers
  * Dropout

---

## Saved Models

The trained models are stored inside:

```bash
models/
```

Files:

* `cnn_model.keras`

---

## Notebook

The complete experimentation and training process is available inside:

```bash
notebooks/experimentation.ipynb
```

---

## Notes

* Simple architecture focused on correctness
* No transfer learning used
* Minimal project structure
* Built mainly for stable training and clean implementation
* Streamlit app added for easy testing

---

## Future Improvements

* Better modularization
* Data augmentation improvements
* Advanced evaluation metrics
* Deployment optimization
* Cleaner production pipeline structure

```
```
