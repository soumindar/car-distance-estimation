# Night Time Vehicle Distance Estimation Based on Monocular Vision

This repository contains Python algorithm to detect vehicle and estimate the distance at night.

The vehicle detection process uses segmentation method for the vehicle tail lights that glow red to produce a bounding box around the vehicle tail lights. The vehicle tail lights are located on the right and left sides of the vehicle, so the width of the vehicle in the image can be calculated based on the width of the bounding box of the vehicle tail lights.

The vehicle distance estimation process uses a method based on the width of the vehicle. The vehicle distance estimation is calculated based on the actual width of the vehicle, the camera focal length and the width of the vehicle in the image.

Testing using 120 digital image data with varying distances, lightings and vehicle types resulted in a recall value of 89,5% and a precision value of 100% for the vehicle detection process, as well as an MSE value of 3,41 meters and a maximum absolute error of 5,725 meters for the vehicle distance estimation process.
