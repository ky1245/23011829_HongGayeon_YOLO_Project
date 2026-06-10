# Custom Object Detection with YOLOv5

## Short description of the project
This project demonstrates a simple object detection pipeline using the YOLOv5 model and PyTorch. It processes an uploaded user image, detects various objects, draws bounding boxes with confidence scores, and prints the total number of detected objects to the console.

## Tools and libraries used
* **PyTorch / torchvision:** Deep learning framework for loading and running the model.
* **YOLOv5 (Ultralytics):** Pre-trained object detection model.
* **OpenCV (opencv-python):** Image processing and drawing bounding boxes.
* **NumPy:** Numerical operations and array handling.
* **Google Colab:** Cloud-based Python execution environment (T4 GPU).

## How to run the code
1. Open the `code.ipynb` file in Google Colab.
2. Change the runtime type to **T4 GPU** (`Runtime` > `Change runtime type`).
3. Run the installation cell to install the required packages.
4. Run all subsequent cells (`Runtime` > `Run all`).
5. When the file upload prompt appears, select and upload your `input_image.jpg`.
6. The script will automatically detect objects and save the final image as `output_result.png`.

## Input image description
* **Image:** `input_image.jpg`
* **Description:** [이곳에 본인이 사용한 이미지에 대한 짧은 설명을 적어주세요. 예: A photo of my study desk with a laptop, a coffee cup, and some books.]

## Output result explanation
The model successfully processed the input image and detected [이곳에 총 탐지된 객체 개수를 적어주세요. 예: 5] objects. 
The output image shows bounding boxes around each detected object along with its class name (e.g., [이곳에 탐지된 물체 이름 예시를 적어주세요. 예: laptop, cup]) and confidence score. The code was also modified to print the total number of detected objects directly to the console.

## Screenshot / Output image
![Output Result](output_result.png)

## 📄 License information
This project is licensed under the **MIT License**.
