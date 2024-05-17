# 🚗 License Plate Recognition Model Enhanced with YOLOv9 🅿️

This project aims to detect license plates in images using the YOLOv9 object detection model. The dataset used for training is available on Roboflow [here](https://universe.roboflow.com/car-speed-estimation/lph_yv9).

## 📂 Dataset

The dataset comprises images of cars with annotated license plate bounding boxes. It includes a variety of license plate types and environmental conditions to enhance model robustness.

## 🛠️ Model Development

The project leverages the YOLOv9 object detection model, known for its speed and accuracy. It is implemented using PyTorch and trained on the Roboflow dataset. The training process involves fine-tuning the pre-trained YOLOv9 model to specialize in license plate detection.

## 🚀 Usage

To run the project in Colab:

1. [Access the Colab notebook from here](https://colab.research.google.com/drive/1Jlg07L8F7cYtL_l0sf-HzEJe7CCnBVsu?usp=sharing).
2. Execute the code cells sequentially to download the dataset, train the model, evaluate its performance, and test it on your own images.
3. Make sure to change the my_images_path variable to point to your own directory of images containing license plates.

## 📋 Requirements

- Python
- PyTorch
- YOLOv9
- Roboflow API Key
- OpenCV
- Matplotlib
- tqdm

## 📊 Evaluation

The model's performance is evaluated using the F1 score, a metric that combines precision and recall to provide a balanced assessment of detection accuracy. Additional metrics like precision and recall are also calculated.


## Contributing 🤝

Contributions are welcome! Please open a Pull Request or report issues.

## License 📄

This project is licensed under the MIT License.

## Contact 📬

Tuncay Özalıcı - tuncay.ozalici@gmail.com - [GitHub](https://github.com/Tuncayozalici) - [LinkedIn](https://www.linkedin.com/in/tuncay-özalıcı)

