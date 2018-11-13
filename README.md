## Image-Communication-Project
The aim of the project is to send the best quality image in 75 seconds using ham radio. 

At transmitter side, we first decompose the figure into raw data and using JPEG algorithm to transform our data into some coefficient and set a threshold value according to the oringinal data size so that we are able to comprass the data into approprate size. After that, adopting GZip algorithm to impression the data further (to about 70 kb). Using ASFK1200 algorithm to chunk those datas into packages and using one ham radio to send the package. 

At receiver side, after we receive the data from the receive ham radio, we do the inverse transform to recover the figure from its reduced coefficient.

## Team Information
- College: University of California, Berkeley
- Institude: EECS 
- Instructor: Prof. Michael (Miki) Lustig
- Course: EE123: Digital Signal Processing
- Date: Apr. 2018

## Team Member
- Xiuneng Lu ([@lUxIUNENG](https://github.com/LuXiuneng))
- Hao He

## Key Algorithm 
- Data Compression: JPEG & GZip

- Data Transmission: ASFK1200

## Demo
Here's our Demo Video:
[![Imagine Communication Project DEMO](EE123_figure.png)](https://youtu.be/uB5SvKIxKjo)
