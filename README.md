# Vehicle-detection-tracking-and-classification using CNN
Vehicle detection, tracking and classification from video feed

![alt text](https://github.com/Ashutosh27ind/Vehicle-detection-tracking-and-classification/blob/main/vehicle_tracking.PNG?raw=true)

## Problem statement  
The problem statement is to detect and identify vehicles in videos. Suppose you want to identify how many vehicles have passed in a lane during peak hours in a city. The purpose of doing this exercise might be multiple:  
1.	The government can use traffic flow data to decide the width of a new road in a nearby area.  
2.	The organisation who's building a highway can decide the toll rate based on the number of vehicles passing on a particular road.  
3.	The government often wants to ban certain types of vehicles (such as auto-rickshaws, trucks, etc.) based on the frequency of these vehicles on a particular road.  
 
Broadly speaking, to achieve any of those tasks, there are two steps involved:  
1.	**Vehicle detection**: Here, you detect those vehicles which are moving on a road.
2.	**Vehicle classification**: Here, you classify the detected vehicle into a particular class according to the application you're working on. For example, if you're interested in looking at the number of four-wheelers vs the number of two-wheelers, you'd classify each vehicle as a two-wheeler or a four-wheeler. Similarly, you can have classes such as auto-rickshaws, trucks, motorcycles, bicycles, etc. The exact classes need to be defined according to the problem statement.  


### Vehicle detection:  
•	The first step is to break a video into individual frames.  
•	Then, make an imaginary (virtual) line across the lane.  
•	To keep the track of the vehicles, increase the vehicle count by one whenever a vehicle crosses the imaginary line.  
 
### Vehicle classification:
•	Crop the vehicle that just passed the imaginary line.  
•	Classify the cropped vehicle using a CNN classifier.  

### Data Source:  
The recorded video file from the below source:  
https://drive.google.com/file/d/1HxxhIf4dM7VILIb5-dR3qXDbeGPOLgv-/view  







