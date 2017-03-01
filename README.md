# Image_processing
Login to facebook using face recognization 

#Basic image processing


from SimpleCV import *
# Initialize the camera
cam = Camera()
# Initialize the display
display = Display()
# Snap a picture using the camera
img = cam.getImage()  
# Show the picture on the screen
img.save(display) 
