# Vehicle Tracking System

This innovative tool is designed to analyze surveillance camera recordings accurately, detecting and counting vehicles passing through a specified area. Leveraging a custom YOLO V8 model, the application is capable of recognizing various vehicle classes such as cars, SUVs, trucks, bicycles, axles, articulated vehicles, and bikes among others.

**Goal:**

The goal of this application is to provide accurate vehicle detection, tracking, and counting capabilities for surveillance camera recordings. By utilizing advanced computer vision techniques and a custom YOLO V8 model, the application aims to meet the needs of clients operating toll tax cameras, assess traffic flow, and revenue generation across different vehicle types.

**Functionality**

**Video Processing**

  1. Single File or Folder Upload: Users can choose to upload a single video file or a folder containing multiple video recordings for analysis.
  2. Frame Processing: Frames from the video are processed to draw coordinates for vehicle tracking.
  3. Starting and Ending Points: Users can mark the starting point and ending point to establish the threshold where a crossing is recorded.
  4. Region of Interest: Users can define a region of interest to focus detection efforts within a specific area of the video.

**Vehicle Tracking and Counting**

  1. Continual Tracking: Continual tracking ensures accurate vehicle counting by incrementing the counter only upon a vehicle passing the defined threshold.
  2. Multiple Points and Regions: Users can establish multiple starting points, ending points, and regions of interest, each contributing to vehicle counting independently.

**Video Processing and Reporting**
  1. Processing Time: Video processing time varies depending on the video's duration and frame rate.
  2. Automated Reporting: The application generates a saved video file and accompanying Excel sheet for analysis, showcasing vehicle detection, tracking, and counting results.

**How to Use**
  1. Upload Video: Choose to upload a single video file or a folder containing multiple video recordings.
  2. Define Tracking Parameters: Mark the starting and ending points for vehicle tracking and define regions of interest as needed.
  3. Initiate Processing: Start the video processing, which may take a few minutes depending on the video's duration and frame rate.
  4. Review Results: Once processing is complete, review the generated video and accompanying Excel sheet for vehicle detection, tracking, and counting results.
  5. Analyze Report: Analyze the generated report to assess traffic flow and vehicle counts across different vehicle types.

Click on the image below to see the video:

[![Vehicle_Tracking_Demo](http://img.youtube.com/vi/Ubv8ce_3ahk/0.jpg)](http://www.youtube.com/watch?v=Ubv8ce_3ahk "Vehicle_Tracking _Demo")
