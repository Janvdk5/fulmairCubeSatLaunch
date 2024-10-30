# fulmairCubeSatLaunch
# Endeavour Rockets Payload Team - Exoplanet Probe CubeSat

Welcome to the **Endeavour Rockets Payload Team** GitHub repository! This repository contains the software suite developed for our Exoplanet Probe CubeSat, scheduled for launch on the Fulamir rocket in 2025. The CubeSat's mission is to detect life on distant planets and includes; Bio and technosignature sensors, general telemetry, microbial air sampler and live object detection using images taken from onboard cameras.

## 🚀 Project Overview

The **Mr Puffinoid** CubeSat focuses on proving our concepts of life on exoplanets. By launching on the Fulamir, we aim to capture and analyse lots of data using a combination of onboard processing and sensor systems, and hopeully return a likelyhood of life being present on the analysed planet, as well as the chances of said life being intelligent.

Key software systems include:
- Sensor interface and data collection modules
- Communication and sequencing protocols between CubeSat’s main processors (Raspberry Pis)
- Object detection algorithms for in-flight object detection of on-ground features and analysis

### Folder Details

- **`sensor_board/`**: Holds code for the zero 2w which runs the bio + technosignature sensors as well as the general telemtry sensors.
  
- **`main_brain/`**: This folder houses the primary control software that coordinates operations among the CubeSat’s multiple Raspberry Pis. Our Pi5 runs the show and code to get it to recieve data from our other boards is coming soon

- **`object_detection/`**: Holds code for object detection algorithms, camera control, actuator control and set-up. All is written for the Pi5
  
- **`microscope/`**: Holds code for the zero 2w which runs the Microbial air sampler experiment

- **`general/`**: Contains any extra code used for testing or to try new sensors/ other unneccesary things.

## 🛠️ Setup & Usage

### Requirements

- **Python 3.8+**
- **Hardware**: Raspberry Pi 5, 2 Pi zero 2ws, Cameras, Stepper Motors, gas and telemtry sesnors each with the necessary interfaces.


## 🤝 Contributing

Contributions are welcome from members of 2023 Darwin-payload and Darwin-software, please just let us know before you do! Open an issue or submit a pull request if you would like to improve the codebase.

## 📬 Contact

For more information about the rocktry team, please reach out to the Endeavour Rockets Payload Team at **[team@endeavourrockets.com](mailto:team@endeavourrockets.com)**.

---
