# R-Cell
<p align="center"><img src="https://user-images.githubusercontent.com/84843295/145799465-e01ccde2-fd06-43af-b835-e843666bb24b.png" /></p>
The project aims at building its own cryptocurrency from scratch using block chain technology. The project uses Python language along with Flask Frameworks to deploy it on a localhost server. This project therefore not only gets us to know about block chain, encryptions and keys but also brings us closer to the world of cryptocurrency whose value is increasing day by day in the modern era.

## Table Of Contents
* [Introduction](#introduction)
  * [About Project](#about-project)
  * [Tech-Stack](#tech-stack)
  * [File Structure](#file-structure)
* [Getting Started](#getting-started)
  * Pre-requisites
  * Usage
* Approach
* Theory
* Result and Demo
* Trouble Shooting
* Contributors
* Mentors
* Acknowledgement

## Introduction

### About Project
The project uses Blockchain Technology by implementation through Python and Flask in the backend for a server. It further uses SQL database for storing the user data such as password, username, email, account balance etc. Through HTML/CSS and JavaScript the Blockchain is deployed on a website. The website is on a local-host which is provided a server through ngrok. This project enhances the knowledge of blockchain technology which has a very high potential in future.

### Tech-Stack
* Python
* Block-Chain
* Flask
* MySQL
* Sha256

### File Structure
```
R-Cell(main)
├─ static                   
│  ├─ css                   
│  │  ├─ index.css          
│  │  ├─ layout.css         
│  │  ├─ login.css          
│  │  └─ register.css       
│  └─ images                
│     ├─ background.jpeg    
│     ├─ favicon.ico        
│     ├─ favicon2.png       
│     ├─ home.png           
│     └─ profile.png        
├─ templates                
│  ├─ handlers              
│  │  └─ 404.html           
│  ├─ includes              
│  │  ├─ _formhelpers.html  
│  │  └─ _messages.html     
│  ├─ buy.html              
│  ├─ dashboard.html        
│  ├─ index.html            
│  ├─ layout.html           
│  ├─ login.html            
│  ├─ register.html         
│  └─ transaction.html      
├─ app.py                   
├─ blockchain.py            
├─ forms.py                 
└─ sqlhelpers.py
 ```
 ## Getting Started

### Pre-requisites
The project involes the installation of following libraries and environment:
* Firstly obviously you should have [Python3](https://www.python.org/downloads/).
* Some basic libraries and frameworks will come pre-installed but you'll require MORE!!
* [Flask](https://flask.palletsprojects.com/en/2.0.x/): This the the framework that supports the website so installing this is a must else it'll throw ERRORS!!
  
  For installation copy and paste the following *mantra* in the prompt
  ``` 
  pip install flask
  ```
  
* [Requests](https://pypi.org/project/requests/): This module is used only once :(, but none the less it is important.
  
  Use the *mantra*:
  ```
  pip install requests 
  ```
  
* [An SQL connection with Flask](https://flask-mysqldb.readthedocs.io/en/latest/): This library ensures a connection between the MySQL Database and the Flask framework.
  
  Use the *mantra*:
  ```
  pip install flask-mysqldb
  ```
