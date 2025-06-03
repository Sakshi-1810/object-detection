# object-detection
Real time object detection using yolov8

# YOLOv8 Object Detection - Images and Videos

This repository contains a YOLOv8-based object detection pipeline that supports both image and video input. The detections are saved in an `output/` folder.

---

## 📁 Folder Structure

project/
│
├── main.py # Main script for running YOLOv8 inference
├── input/ # Input folder for images and videos
├── output/ # Output folder for annotated images and videos
├── requirements.txt # Python dependencies
└── README.md # Documentation

yaml
Copy
Edit

---

## 🔧 Requirements

- Python 3.8+
- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- OpenCV

Install dependencies using:

```bash
pip install -r requirements.txt
Contents of requirements.txt:

nginx
Copy
Edit
ultralytics
opencv-python
▶️ How to Use
Add input files
Place your images (.jpg, .png) or videos (.mp4, .avi) in the input/ folder.

Run the detection script

bash
Copy
Edit
python main.py
Check results
Processed images/videos with detections will be saved in the output/ folder.

🧠 main.py Overview
The script:

Loads YOLOv8 model (default: yolov8n.pt)

Detects objects in each image or video

Draws bounding boxes and saves output

You can customize the model path or confidence threshold in the script.

🖼️ Example
Input: input/street.jpg

Output: output/street.jpg with detected objects

📄 Notes
Make sure input/ and output/ folders exist in the project root.

The script automatically detects file types based on extensions.

📬 Contact
For issues or suggestions, feel free to open an issue or pull request.
