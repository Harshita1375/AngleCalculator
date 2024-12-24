# AngleCalculator
The Angle Calculator model utilizes Python and OpenCV to detect and calculate angles by identifying the key points or lines in the input, the model computes the angle between them .

## How It Works  

1. **Load the Image**: The script reads the image (`Angle.jpge`) and prepares it for annotation.  
2. **Mouse Clicks**:  
   - Left-click on the image to mark points.  
   - Three points are required to form an angle.  
3. **Angle Calculation**:  
   - Uses the slope (gradient) formula to compute the angle between two lines originating from the first point.  
   - Displays the calculated angle on the image.  
4. **Reset**: Press `q` to reset the points and reload the image.  

### Requirements  
- Python  
- OpenCV library (`pip install opencv-python`)  

### Expected Output  
The angle between the selected points will be displayed on the image in degrees (Refer 'output.mp4' to verify the outpu).
