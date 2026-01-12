Road Damage Detection with YOLO

This project tackles the problem of spotting road damage—things like potholes, cracks, and manholes—using computer vision and deep learning. 
The idea is simple: train a model on labeled road images so it can find and classify damage automatically. 
That way, road crews and city planners get real data for maintenance and safety, without all the manual inspection.

Project Overview:

- Detects road damage in photos
- Uses YOLO for object detection
- Picks out three damage types: pothole, crack, manhole
- Built and tested with Python and deep learning libraries

Technologies Used:

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

Project Structure:

road-damage-detection-yolo/
│
├── road-damage-detection.ipynb   # Main notebook
├── README.md                     # Docs
├── .gitignore                    # Ignore rules

Dataset Details:

- Preprocessed and normalized images
- Labels:
  0 = pothole
  1 = crack
  2 = manhole
- Data split into training and test sets
- Checked class balance before training

Installation & Setup:

1. Clone the repo

2. Install requirements:
   pip install numpy tensorflow matplotlib opencv-python scikit-learn tqdm

3. Run the notebook:
   jupyter notebook

Model Workflow:

1. Load and prepare images
2. Normalize the data
3. Encode labels
4. Train the YOLO model
5. Check how it performs
6. See predictions in action

Results:

- Finds and classifies road damage pretty well
- Handles all three types smoothly
- You can even build on this for real-time detection

Future Enhancements:

- Bring in real-time detection on video
- Turn it into a web or mobile app
- Add GPS so you know where the damage is
- Boost accuracy with more data
