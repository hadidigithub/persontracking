# persontracking
Project 2: Person Tracking AI for Indonesia

#download
Download link
https://drive.google.com/file/d/1cxlyp0SVDFRONJct6viZK6rQG3wU1zK7/view?usp=sharing

#pertama
python installed min Python 3.11.5

#kedua install library
pip install -r requirements.txt

#cara menjalankan, buka command dan masuk ke directory
#jalankan untuk gambar dan video
python detection.py --model yolov8n.onnx --source data\images\contoh1.jpg
python detection.py --model yolov8n.onnx --source data\videos\video2.mov

#jalankan untuk webcam
python detection.py --model yolov8n.onnx --source 0
