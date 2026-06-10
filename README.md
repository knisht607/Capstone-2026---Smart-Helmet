**Abstract:**
Cyclists often ride alongside vehicles on high-speed roads or in areas without dedicated bike lanes, forcing them to turn their heads to check blind spots. This reduces awareness and can impact stability, while existing solutions lack real-time, helmet-integrated detection. This project introduces RideAware, a smart helmet that detects approaching vehicles and provides intuitive haptic feedback and hands-free signaling. The system is designed to deliver real-time alerts based on the position of nearby vehicles, allowing riders to react quickly without shifting their focus. By integrating these features into a single wearable platform, it improves awareness while maintaining comfort and ease of use, ultimately enhancing overall safety and rider confidence.

**System Design:**
A rear mounted camera continuously captures the FOV behind the cyclist and sends recorded data to the Raspberry Pi 5 to be processed.
Utilizing the YOLOv4-Tiny lightweight computer vision model, it identifies approaching vehicles and estimates their position relative to the rider.
Two DRV8833 motor drivers control the vibration motors on the interior of the helmet. Each side has one motor in the front and one in the rear.
Rider can activate or deactivate LED turn indicators with 2 head tilts to left or right side. 

**Project Cost:**
The total prototype cost for RideAware is approximately $200-$215, primarily driven by processing hardware, sensing components, and power management.
Cost efficiency can be improved through bulk purchasing, custom PCB integration, and optimized component selection. In small-scale production (100–500 units), the estimated cost per unit could be reduced to approximately $110–$130. Additional reductions are possible by replacing development boards with dedicated embedded hardware and simplifying the overall system design.
