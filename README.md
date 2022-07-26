# Face-Recognition with OpenCV and Deep Learning
Implement a deep learning based facial recognition using OpenCV and Python

# Usage
1. Build a dataset of facial images to train the model to recognise faces in images or video stream. 
Run build_face_dataset.py to create your custom dataset of example faces.
Store face images organised into subdirectories based on their respective names.
2. Build a serialised db of facial encodings to disk: <code>$ python encode_faces.py --dataset path/to/directory/of/faces --encodings path/to/serialised/db</code>
3. Recognise faces in images:
   <code>$ python recognize_faces_image.py --encodings path/to/serialised/facialencodings/db --image path/to/input/image</code>
4. Recognise faces in a video file:
   <code>$ python recognize_faces_video_file.py --encodings path/to/serialised/facialencodings/db --input path/to/input/video</code>
5. Recognise faces in real time video:
   <code>$ python recognize_faces_live_video.py --encodings path/to/serialised/facialencodings/db</code>
  
