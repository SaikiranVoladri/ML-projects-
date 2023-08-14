<h2> Machine learning Project <h2><br>
<h1>Face Mask Detection </h1>
  
![github_withmask](https://github.com/SaikiranVoladri/ML-projects-/assets/87108573/ac35f0d4-65af-4b40-8801-639e4e2c0635)

# Real-Time Face Mask Detection using Deep Learning

This repository contains a Python script that demonstrates the creation and training of a real-time face mask detection system using deep learning techniques. The MobileNetV2 architecture is employed as a base model, with additional layers added for classification. The script preprocesses images, applies data augmentation, and uses an image data generator for training. The model is compiled and trained using the Adam optimizer. The performance is evaluated using a classification report, and the trained model is saved to disk. A plot showing training loss and accuracy over epochs is also generated.

## Getting Started

To run the code and replicate the face mask detection system, follow these steps:

1. Install the required dependencies using the following commands:
pip install tensorflow
pip install keras

2. Download the code from this repository.

3. Download the dataset of face images with and without masks and organize it as follows:
- Create a directory named 'dataset'.
- Inside 'dataset', create subdirectories 'with_mask' and 'without_mask'.
- Place face images with masks in the 'with_mask' directory and images without masks in 'without_mask'.

4. Run the Python script `mask_detection.py` using the following command:


## Video Demonstration

For a detailed explanation and demonstration of the code, watch the video tutorial on YouTube: [Face Mask Detection Video Tutorial](https://drive.google.com/file/d/1CFRpK13JQ6cgfhQUxDj8bWdUw1NfQiVd/view?usp=sharing)

## Results

The script provides a real-time face mask detection system with accuracy and loss metrics displayed in a plot.

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss the proposed changes.

## License

This project is licensed under the [MIT License](LICENSE).

