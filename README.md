# CV Counter - Computer Vision Footfall Counter

## Project Overview

CV Counter is a computer vision-based footfall counter designed to accurately count and track the number of people passing through entrances and exits. This project leverages advanced computer vision techniques to provide real-time visitor counting for various applications including retail stores, events, offices, and public spaces.

The system is particularly effective when deployed with camera feeds positioned at entrance or exit points, making it an ideal solution for businesses and organizations looking to monitor foot traffic and analyze visitor patterns.

## Features

- **Real-time Footfall Counting**: Accurate detection and counting of people using computer vision
- **YOLO-based Detection**: Utilizes state-of-the-art YOLO object detection for reliable person identification
- **Easy Demo Integration**: Includes ww.mp4 demo video for quick testing and validation
- **Google Colab Ready**: Seamless integration with Google Colab notebooks for easy deployment
- **Flexible Deployment**: Works with live camera feeds or pre-recorded video files
- **Entrance/Exit Monitoring**: Optimized for monitoring traffic at entry and exit points

## Usage

### Running in Google Colab

1. **Open the Notebook**: Upload `Footfall_counter.ipynb` to Google Colab or open it directly if you have the repository cloned
2. **Install Dependencies**: Run the first cell to install required packages:
   ```python
   !pip install ultralytics
   ```
3. **Upload Video**: Upload your video file or use the provided `ww.mp4` demo video
4. **Run the Counter**: Execute the main cells to start the footfall counting process
5. **View Results**: The notebook will display real-time counting results and statistics

### Running Locally

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/MishrajiAryan/cv_counter.git
   cd cv_counter
   ```

2. **Install Requirements**:
   ```bash
   pip install opencv-python ultralytics numpy matplotlib
   ```

3. **Run the Demo**:
   ```python
   python Footfall_counter.ipynb  # If converted to .py
   # OR open in Jupyter Notebook
   jupyter notebook Footfall_counter.ipynb
   ```

### Demo Video Instructions

- Use `ww.mp4` as a sample video to test the system
- The demo showcases the counter's ability to detect and count people in various scenarios
- Replace with your own video feed for real-world applications

## Where This Is Useful

### Primary Applications

- **Retail Analytics**: Count customers entering/exiting stores to analyze foot traffic patterns
- **Event Management**: Monitor attendee flow at conferences, exhibitions, and public events
- **Office Buildings**: Track employee and visitor movement through entrances
- **Transportation Hubs**: Count passengers at subway stations, bus stops, and airports
- **Security Monitoring**: Enhance security systems with accurate people counting
- **Smart Buildings**: Integrate with building management systems for occupancy tracking

### Specific Use Cases

- **Entrance Monitoring**: Position cameras at main entrances for comprehensive visitor tracking
- **Exit Analysis**: Monitor exit patterns to understand peak hours and crowd behavior
- **Capacity Management**: Ensure compliance with occupancy limits in various venues
- **Business Intelligence**: Generate insights on customer behavior and peak operating hours
- **Resource Planning**: Optimize staffing and resources based on traffic patterns

## Demo

The repository includes `ww.mp4`, a demonstration video that showcases the footfall counter in action. This video serves as:

- A quick way to test the system without setting up live camera feeds
- A reference for expected input video format and quality
- A benchmark for validating the accuracy of the counting algorithm

Simply run the notebook with `ww.mp4` as input to see the counter's capabilities.

## Technical Requirements

- Python 3.7+
- OpenCV
- Ultralytics (YOLO)
- NumPy
- Matplotlib
- Google Colab (optional, for cloud execution)

---

**Getting Started**: Begin with the `ww.mp4` demo video and `Footfall_counter.ipynb` notebook to quickly understand the system's capabilities. For production use, position cameras at entrance/exit points for optimal counting accuracy.
