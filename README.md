# Change Detection in Multi-temporal Satellite Images  
[ INDP3 AIM 2019/2020 - SUPCOM ] Project : Change Detection in Multi-temporal Satellite Images  
Realized by :  
• **Ihebeddine Riahi** : ihebeddine.riahi@supcom.tn  
• **Chaima Bouzaidi** : chayma.bouzaidi@supcom.tn  

## Table of contents
1. [Overview](#Overview)
2. [Requirements](#Requirements)
3. [How to detect change?](#How)


<a name="Overview"/>  

## Overview
This project aims to detect changes in multi-temporal satellite images.  
It uses Principal Component Analysis (PCA) and K-means clustering techniques over difference image.  

<a name="Requirements"/>

## Requirements
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; • Install OpenCV (version 4.2.1).  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; • Install Python (version 3.6.9).  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; • Scikit-learn ML Library.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; • The directory `images` contains multi-temporal images developed from the LANDSAT images available United States Geological Survey (USGS) website.   


<a name="How"/>

## How to detect change? 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; • Go to `scripts` directory and Run `python3 DetectChange.py -io <FIRST_IMAGE> -it <SECOND_IMAGE> -o <OUTPUT_DIRECTORY>` to detect change in two multi-temporal satellite images.  
**NB**: The output directory should end with '/'.   
The script will generate a difference image named `difference` and a `ChangeMap` image.   
Other images are generating depending on morphological transformations.