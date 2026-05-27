# Colour Detection using OpenCV

## Overview

Colour Detection using OpenCV is a simple Computer Vision project developed with Python and OpenCV. The project detects and identifies colors in real-time using a webcam or image input. It processes frames, extracts pixel values, and displays the detected color name along with bounding details.

---

## Features

* Real-time color detection
* Webcam and image support
* Displays detected color names
* Bounding rectangle for detected objects
* Simple and beginner-friendly implementation
* Built using Python and OpenCV

---

## Technologies Used

* Python
* OpenCV (cv2)
* NumPy

---

## Project Structure

```bash
Colour_detection_cv2/
│
├── color_detection.py
├── colors.csv
├── images/
├── README.md
└── requirements.txt
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/Colour_detection_cv2.git
```

### Navigate to the Project Folder

```bash
cd Colour_detection_cv2
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Requirements

```txt
opencv-python
numpy
pandas
```

---

## Run the Project

```bash
python color_detection.py
```

---

## Working Process

1. Capture image/video frame
2. Detect pixel coordinates
3. Extract RGB values
4. Match nearest color from dataset
5. Display color name on screen

---

## Sample Output

### Real-Time Color Detection

![Image](https://images.openai.com/static-rsc-4/fFi3eopyZgLl7tn5cmyYTJBN2IX0g8Hh383_hLCSa8NFSQCoZ2WWznWv3sSNIvfTZJxKSHh_p1jY-MgY2HATiWIsnsHuP5X9zLTKNN0uCFpt8grBGLD5E408awJ9wteukvNupKbcWbkzObOIbTarSbJZg31ZKuluHloDfnKuRmWpBEeRvdOFLobmZ1shrSwk?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/wAGaZkOrwRu5iEzvMyK8I3QTfD-_jROzVvurGMq6nNGA_vVWKptTWwV7BhK-pAHL4OsiLQAAEsZo3tesODjI9bsZeRO-3EYJR_tRyNIig16Mj5aaxHLl2EdVEDxgdtqMCyNhg1HvoJ30MCmYqq_HCgTLjXekB1-bII5BmsC__k3kHz7cOO12dEuJ_7UPbohX?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/OMvxuAEj30FrS2BDaCKzjUybPnOfhy6QqEFk8yOsxW8IcnP1Mh8mfxeu8g1YPmGZGILFZomk-rMGlIpq1ujU4nDKOLhnoLhK25OTxCG3wjik_7W8GskBG61ib1OR-RDjJwGV95QUG6EW-XK9PuJYvyvNQ8J_HS0B1cX1jyzZ2-b9mVe-Fa3IpXWBcdwshcJA?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/VpaaOXFw06MFGHMLsb4nzjtKnHPVaVCPQcnK_CWf2puyTl2p7vaC4qQfM83m3gaRXmO_tLWrZ3SKSbFJ-ceyT73SSpy1Z6yF0wzLQkg4S-TBxf5yWh3XfX5si1Q1TvJaHSHhfQTv3b5teLgTjjD_y3YSmNtIntV4qZfd0PU9V_vX76QQKVnh5V7ze6aBAqZ3?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/u7cV50-9q93-qIkenmGd0FXGCB2MLWbTrCOp_4QbYXfRK-5CrPoM7iEQ1x4hz4jVrECRf-UcuCDiS6m3u2ovlJ4iZLBuFzHbFw0dTCfNARjeiYcsHlUX-BfT3d5VrkDREfflgGgf8qhhDbRPAhzWE9jZtc3FjORev9fZDoi_vNW-Sks4i7AzFAqX6U2p17uI?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/OLlMySXQ4EyB9IL4_0Zvuzk_TSDaolaH-dhTNsvOmmoSmGpUl2fYVxJjLrn2Ih9joK4FDzM30ovhvFxx1AkMpfrz308N-nCz73UiyUTcZ_cqlJ9wWfhTyExAMEjZIV9CTADMN-sPc7wCFLOyB9YlTDRvG9yl9aE1HGo2rbC_tRHVf_HiHKiB0Z0T6f0M3HXo?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/kuF0sUx8A3hbKmX-tiEJj84MT2KdYop8WwmKbcm8cOa0NI4QX9XC3jBL_mFbs2ZJpMvEnVxSSfJfOOkIGgSLXd7cXADLOt0_SwPbFeZJMppMW4gful-6_Jy7CfuQNCDV98piHxGBj0tIoTey8uGKemomlCK-_gwxiRqXEDq6OAutkwRQLapMyQPdrdk02dkN?purpose=fullsize)

### Color Detection Workflow

![Image](https://images.openai.com/static-rsc-4/-MtZY4GQI0sS9MTWjufKVViM_Qu3Ce1ay8cK4k48n_O2E7zSrjuixwn2cvC8srG9kfWhPgqWCa-9Ev36tVJaOszYrCQ8oxpQP3Dem2jnA1Q2KiO7sSTzC_ODoYov3wEW3K-YH7ZSmZdm-nUP_DeQn03a-Lwg94q0bUJrKQ80ssSGNyNKob4J696O7sXEXYpb?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/OMvxuAEj30FrS2BDaCKzjUybPnOfhy6QqEFk8yOsxW8IcnP1Mh8mfxeu8g1YPmGZGILFZomk-rMGlIpq1ujU4nDKOLhnoLhK25OTxCG3wjik_7W8GskBG61ib1OR-RDjJwGV95QUG6EW-XK9PuJYvyvNQ8J_HS0B1cX1jyzZ2-b9mVe-Fa3IpXWBcdwshcJA?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/YfIPzf7l_CmjTV9x-bPZDml8GlnlyU9zADPzeuaVk95oxyywPTto-qU9Ob2KSWT6TXLCiLQJ9RRX-VWzcZelrcccUaU5GhwiHK8zjOKDENQxxeIpz1J6r8YEopcX9lvx7RkpREkV6jaPPjKM0yMg9lEapp78Clir3dB0qGygvSjHCCpIjpCrzHmCmEUUc5NG?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/wAGaZkOrwRu5iEzvMyK8I3QTfD-_jROzVvurGMq6nNGA_vVWKptTWwV7BhK-pAHL4OsiLQAAEsZo3tesODjI9bsZeRO-3EYJR_tRyNIig16Mj5aaxHLl2EdVEDxgdtqMCyNhg1HvoJ30MCmYqq_HCgTLjXekB1-bII5BmsC__k3kHz7cOO12dEuJ_7UPbohX?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/Enybslc25zvePKAbxhYTCqm5dV-umctOtchuCHbmYz5r3Gw_rYEvqCAzIFEKLyexGnxZhurILYRfCBmnRNy_uez4lCQ-AhtdKZQmgwMzZcO8AWJVGUPjOG9B7rGnKImady01DnBpcBpRAfbuZO1N1161h_sJmcEJpK2qcUAXiQDB1Xi1mogsmCOzCcIuMUCw?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/u7cV50-9q93-qIkenmGd0FXGCB2MLWbTrCOp_4QbYXfRK-5CrPoM7iEQ1x4hz4jVrECRf-UcuCDiS6m3u2ovlJ4iZLBuFzHbFw0dTCfNARjeiYcsHlUX-BfT3d5VrkDREfflgGgf8qhhDbRPAhzWE9jZtc3FjORev9fZDoi_vNW-Sks4i7AzFAqX6U2p17uI?purpose=fullsize)

---

## Applications

* Object tracking
* Robotics
* Traffic signal detection
* Industrial automation
* Smart surveillance systems

---

## Future Improvements

* Multiple color tracking
* HSV color space optimization
* Deep learning integration
* Mobile camera support

---

## Author

Developed using Python and OpenCV for Computer Vision learning and real-time image processing applications.
