Steps To use it : 

1 - pip install ultralytics 
2- import torch
from ultralytics import YOLO

# Load the best.pt model
model = YOLO('best.pt')

# Load an image (ensure the correct path and extension)
img = 'frames51.jpg'

# Perform inference
results = model(img)

# Print the results
print(results)
3- In the terminal use this command 
yolo predict model=best.pt source='frames51.jpg' 
