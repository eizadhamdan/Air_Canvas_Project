## Air_Canvas_Project
 
This is an innovative project that brings the magic of digital art to the physical world. 
Using computer vision and ML, Air Canvas allows users to create stunning artwork simply by moving their hands in the air.


# Requirements: 
python3 , numpy , opencv, mediapipe

# Algorithm:
1. Read the frames and convert the captured frames to HSV colour space(easy for colour detection)
2. Prepare the canvas frame and put the respective ink buttons on it
3. Adjust the values of the mediapipe intilization to detect one hand only(to avoid confusion)
4. Detect the landmarks on the hand by passing the RGB frame to the mediapipe hand detector
5. Detect the landmarks, find the index finger coordinates and store them in arrays for successive frames
6. Finally draw the points stored in array on the frames and canvas

# Usage:
1. Clone the Repository
   ```
      git clone https://github.com/eizadhamdan/Air_Canvas_Project.git
   ```
2. Navigate to the Project Directory
   ```
      cd Air_Canvas_Project
   ```
3. Install Dependencies
4. Run the Script:
   ```
      python air_canvas.py
   ```
   
