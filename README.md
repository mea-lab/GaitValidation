# GaitValidation
repository with data and analysis related to video-based gait analysis 


# Run video-based analysis 
1. download the PosePipeline.ipynb file in the "Scripts" folder
2. input participant's height in the video
   
```python
# set up
height_cm = 150
```

3. modify the location of the folder of the video in the code
   
```python
# Set up directories
input_dir = "../Downloads/AFTERTRIM"   
```

4. run the scipt and get the "feature_results.xlsx" file 


# Run correlation 
1. output sensor results by using sensor files in the "sensor data" folder 
2. load sensor result excel and video analysis result excel 
3. run the code cell to get correlation and figures 


# Compare differences between patients and healthy control 
modify this line to the right file in the "LLM analysis" folder 

```python 
df = pd.read_excel(r"C:\Users\shuyu.liu\OneDrive - University of Florida\Documents\GitHub\GaitValidation\LLM analysis\large model", sheet_name="Sheet1")
```
