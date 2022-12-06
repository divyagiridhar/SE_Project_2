# SE_group25_Project_2: WolfComplain2.0

<!-- Head -->

<!-- SHIELDS -->


<a href="https://github.com/divyagiridhar/SE_Project_2/issues">
        <img src="https://img.shields.io/github/issues-closed/divyagiridhar/SE_Project_2" /></a>

<a href="https://github.com/divyagiridhar/SE_Project_2/blob/main/LICENSE"> 
        <img src="https://img.shields.io/github/license/divyagiridhar/SE_Project_2" /></a>

<a href="https://github.com/divyagiridhar/SE-Group-25-WolfCare.git">
    <img src="https://img.shields.io/github/repo-size/divyagiridhar/SE-Group-25-WolfCare?color=brightgreen"></a>
    
<a href="https://github.com/divyagiridhar/SE_Project_2/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/divyagiridhar/SE_Project_2"></a>
    
<a href="https://github.com/divyagiridhar/SE-Group-25-WolfCare">
    <img src="https://img.shields.io/github/languages/count/divyagiridhar/SE_Project_2"></a>
    
<a href="https://github.com/divyagiridhar/SE-Group-25-WolfCare/tags">
    <img src="https://img.shields.io/github/v/tag/divyagiridhar/SE_Project_2"></a>

[![Code Coverage](https://codecov.io/gh/Sanayshah2/SE_Project_1/branch/main/graphs/badge.svg)](https://codecov.io/gh/Sanayshah2/SE_Project_1/branch/main)

[![Django CI](https://github.com/sanayshah2/SE_Project_1/actions/workflows/django.yml/badge.svg)](https://github.com/sanayshah2/SE_Project_1/actions/workflows/django.yml)

[![DOI](https://zenodo.org/badge/537628861.svg)](https://zenodo.org/record/7402637#.Y466FXbMLIU)


[![code checker](https://github.com/divyagiridhar/SE_Project_2/actions/workflows/code_checker.yml/badge.svg)](https://github.com/divyagiridhar/SE_Project_2/actions/workflows/code_checker.yml)


## Introduction

This repository contains source code for Project 2 which was created for CSC 510 course of NC State University Fall 22. This project is an extenstion to the project 1 developed by Team 28. Below is the introduction for the same - Here at NC State each faculty has their own set of rules they use for teaching and grading students. Students are given access to a lot of resources and Moodle website is one such. The site contains all the details related to courses a student has taken, but the Moodle page is overcluttered and there is a lot of data which is unorganised. This leads to faculty using other specialized softwares and platforms like Discord, GitHub, Piazza for tasks like doubt solving, class participation exercises, forums, etc.

This leads to students spending useful time at learning and getting acquitaned to all these different softwares. Students waste time in finding answers to questions like 'where can I find this feature' or 'how do I post this' which could be better spent on productive things. Also finding a particular resource takes more time and as such students tend to ask the same questions again and again. 

This website, WolfComplain, was thus created to tackle this issue. It is specifically designed for doubt solving and class discussions. In our website students can easily track all the questions they have asked so far across all courses. Also they can find all doubts posted for a particular course by all other students. 
We have created tags for all doubts and as such students know the status of all their doubts. With this project we aim to increase the productivity of students and faculty by avoiding time to learn new softwares and lesser chances of same doubts being posted again and again.


## Advertisement Video



https://user-images.githubusercontent.com/70748055/205809252-b1e40954-2490-4e5b-b8ad-59fb8693ea3b.mp4



## Languages
- HTML
- Python 
- Javascript (embedded in HTML)
<p align="right">(<a href="https://github.com/Sanayshah2/SE_Project_1/blob/main/README.md">back to top</a>)</p>


## Installation and Execution
### Method 1:
This method requires:
```
    -Python 3.6 or greater
    -pip (or) pip3  
``` 
1. Install the entire source code from this git repository as a zip file and extract it.
2. Install the necessary packages for the project using the following command - 
``` 
pip install -r reqirements.txt
```
3. Setup the database using the following command - 
```
python manage.py makemigrations
```
4. Create the superuser using the following command - 
```
python manage.py createsuperuser
```
5. Finally start the server using the following command - 
```
python manage.py runserver
```
6. Now the application is running on your local device and you can access the website by goign on the local host port:8000 of your device. 
### Method 2: 
1. Install the Docker Desktop application on your device.
2. Download the docker image file(.tar) using this link https://drive.google.com/file/d/1_-hrrcBlHTl3_KFKhyfN6XwS6KpcxVbP/view?usp=sharing
3. Build docker image using the following command - 
```
docker build --tag <docker-image-name> .

# add the --network=host tag if you run into network problems
```
4. To execute the application, run the docker image which you just created using the following command -
```
docker run --publish 8000:8000 <docker-image-name>
```
5. Now the application is running inside the docker container and you can access the website by goign on the local host port:8000 of your device. 



<p align="right">(<a href="https://github.com/Sanayshah2/SE_Project_1/blob/main/README.md">back to top</a>)</p>

## DOI
[![DOI](https://zenodo.org/badge/537628861.svg)](https://zenodo.org/badge/latestdoi/537628861)

## Requirements
<a href="https://github.com/Sanayshah2/SE_Project_1/blob/main/requirements.txt">REQUIREMENTS.txt</a>

## Documentation
All the documentation related to our project could be found under the docs folder and at this link - https://sanayshah2.github.io/SE_Project_1/
<p align="right">(<a href="https://github.com/Sanayshah2/SE_Project_1/blob/main/README.md">back to top</a>)</p>

<a href="https://github.com/Sanayshah2/SE_Project_1/blob/main/docs/Function%20Descriptions.md">Description of Functions</a>

<a href="https://github.com/Sanayshah2/SE_Project_1/blob/main/docs/Mini-Tutorial.pdf">Mini Tutorials</a>

<a href="https://github.com/Sanayshah2/SE_Project_1/blob/main/docs/motivation.md">Motivation</a>
 
<!-- ## Install
<a href="https://github.com/ShiveshJha12/SE_group28_HW2/blob/main/INSTALL.md"><h4>INSTALL.md</a>  -->

## Deployment:
Our project is deployed at Heroku Platform and you can access it using link - http://complainx.herokuapp.com/
<p align="right">(<a href="https://github.com/Sanayshah2/SE_Project_1/blob/main/README.md">back to top</a>)</p>

## License
[MIT](https://github.com/Sanayshah2/SE_Project_1/blob/main/LICENSE)
<p align="right">(<a href="https://github.com/Sanayshah2/SE_Project_1/blob/main/README.md">back to top</a>)</p>

## Contributors:
1. Elizabeth Lin  
2. Neel Shah  
3. Sanay Shah  
4. Shaival Shah
5. Shivesh Jha    
<p align="right">(<a href="https://github.com/Sanayshah2/SE_Project_1/blob/main/README.md">back to top</a>)</p>
