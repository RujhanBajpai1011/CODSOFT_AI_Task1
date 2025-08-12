# 🖼️ Image Captioning

This project provides a basic **image captioning** system that generates a text description for an input image. It uses a pre-trained **ResNet50** model for feature extraction.

## **✨ Features**

* **Image Feature Extraction**: Leverages a pre-trained ResNet50 Convolutional Neural Network (CNN) to extract features from images.
* **Dummy Caption Generation**: Returns a placeholder "Generated Caption (dummy text)" for demonstration purposes after feature extraction.
* **Simple Interface**: A straightforward class structure for easy prediction.

## **🛠️ Technologies Used**

* **Python**
* **torch**: PyTorch framework for deep learning.
* **torchvision.models**: For pre-trained CNN models (ResNet50).
* **torchvision.transforms**: For image preprocessing.
* **PIL (Pillow)**: For opening and manipulating images.

## **📦 Requirements**

To run this project, you will need the following Python libraries:

* torch
* torchvision
* Pillow

## **🚀 Getting Started**

### **Installation**

1. **Clone the repository (if applicable):**

```
git clone <repository_url>
cd <repository_name>
```

2. **Install the required Python packages:**

```
pip install torch torchvision Pillow
```

### **Usage**

1. **Place the image**: Ensure the image file (`image.png` as referenced in the notebook, or any image you want to use) is in the same directory as the Jupyter notebook (`Image_Captioning.ipynb`).

2. **Run the Jupyter Notebook**: Open and execute the cells in the `Image_Captioning.ipynb` notebook in a Jupyter environment.

The notebook will initialize the captioning model and print a dummy caption for the specified image.

## **🧑‍💻 Contributing**

This is a basic implementation. Feel free to extend it by integrating a proper language model for actual caption generation!

Contributions are welcome! If you have suggestions for improvements, new features, or bug fixes, please feel free to:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/your-feature-name).
3. Make your changes.
4. Commit your changes (git commit -m 'Add new feature').
5. Push to the branch (git push origin feature/your-feature-name).
6. Open a Pull Request.

## **📄 License**

This project is open-source and available under the MIT License.
