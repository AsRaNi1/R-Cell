# R-Cell
<p align="center"><img src="https://user-images.githubusercontent.com/84843295/145799465-e01ccde2-fd06-43af-b835-e843666bb24b.png" /></p>
The project aims at building its own cryptocurrency from scratch using block chain technology. The project uses Python language along with Flask Frameworks to deploy it on a localhost server. This project therefore not only gets us to know about block chain, encryptions and keys but also brings us closer to the world of cryptocurrency whose value is increasing day by day in the modern era.

## Table Of Contents
* [Introduction](#introduction)
  * [About Project](#about-project)
  * [Tech-Stack](#tech-stack)
  * [File Structure](#file-structure)
* [Getting Started](#getting-started)
  * [Pre-requisites](#pre-requisites)
  * [Usage](#usage)
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
<p align="center"><img src="https://user-images.githubusercontent.com/84843295/146186109-84229fdc-d7e7-4159-8619-b26506a2a62f.jpeg" /></p>

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

* wtforms: A python library used for getting inuput from a user in forms
  Use *mantra*:
  ```
  pip install wtforms
  ```
* [Ngrok](https://ngrok.com/): For setting up the server for the website, Ngrok is required. Ngrok creates tunnels across local-host servers to make them behave as decentralized.  Download Ngrok from the link provided.
  1. After installation open your prompt and run the following
  ```
  unzip /path/to/ngrok.zip
  ```
  2. Then open Ngrok and connect it to your account by copying the command provided on the website.
  
## Usage
Assuming you have git, follow the following process
1. Clone the Git Repo:
   ```
   $ git clone https://github.com/AsRaNi1/R-Cell.git
   ```
2. Go into the Repo directory
   ```
   $ cd ../R-Cell
   ```
3. Run the app.py file in the directory
   ```
   $ python app.py
   ```
4. A local-host server address will open
   ![image](https://user-images.githubusercontent.com/84843295/146188192-f851c340-8cd0-42c5-b22f-c4c02a961536.png)

5. Copy the local-host address and then open Ngrok
6. In Ngrok paste the local host link as follows:
   ```
   ngrok http *Your Local host link here*
   ```
7. Viola!! Your Blockchain is up and running, NOW MAKE YOUR FRIENDS REGISTER AND BUY AND SEND R-CELL CURRENCY.

