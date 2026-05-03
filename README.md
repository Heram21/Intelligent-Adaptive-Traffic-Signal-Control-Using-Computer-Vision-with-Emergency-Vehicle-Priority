🚦 Project OverviewThis 
project addresses the inefficiencies of traditional fixed-time traffic signals by introducing an AI-driven Adaptive Signal Control system. By leveraging real-time video processing and deep learning, the system calculates vehicle density to dynamically adjust signal timings, reducing urban congestion and prioritizing emergency services.  
✨ Key FeaturesReal-Time Vehicle Detection: Utilizes the YOLO (You Only Look Once) framework to identify and classify vehicles (cars, buses, trucks, bikes, and ambulances) in real-time.
Adaptive Signal Timing: Replaces static timers with an intelligent algorithm that calculates green signal duration based on actual lane occupancy.
Emergency Vehicle Priority: Features an immediate override mechanism that detects ambulances and clears the corresponding lane to minimize response times.  
Interactive Simulation: A high-fidelity 4-way intersection model developed with Pygame to visualize traffic flow and system performance.
🛠️ Tech StackProgramming Language: Python  
Deep Learning: YOLO 
Simulation & GUI: Pygame 
Libraries: Threading, OpenCV (Image Preprocessing), Math, Random  
🚀 Implementation Workflow
Video Capture: Real-time feed is processed into individual frames. 
Preprocessing: Frames are resized and noise-reduced for optimal detection. 
Density Estimation: YOLO identifies vehicles within a defined Region of Interest (ROI) for each lane. 
Signal Control: The system executes Round Robin scheduling by default, overridden by Adaptive Logic or Emergency Handling as needed. 
📈 Results
Significant reduction in average vehicle idling time. 
Stable traffic throughput even during high-density scenarios. 
Successful prioritization of emergency vehicles without causing lane starvation.
