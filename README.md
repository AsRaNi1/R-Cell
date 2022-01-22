# R-Cell🪙
<p align="center"><img src="https://user-images.githubusercontent.com/84843295/149780409-72a6d505-0f8b-42a3-9738-f4898a2a513c.png" /></p>
The project aims at building its own cryptocurrency from scratch using block chain technology. The project uses Python language along with Flask Frameworks to deploy it on a localhost server. This project therefore not only gets us to know about block chain, encryptions and keys but also brings us closer to the world of cryptocurrency whose value is increasing day by day in the modern era.

## 📃Table Of Contents
* [Introduction](#introduction)
  * [About Project](#about-project)
  * [Tech-Stack](#tech-stack)
  * [File Structure](#file-structure)
* [Getting Started](#getting-started)
  * [Pre-requisites](#pre-requisites)
  * [Usage](#usage)
* [Glimpses](#Glimpses)
* [Google Drive Link](#gdrive)
* [Trouble Shooting](#trouble-shooting)
* [Future Scope](#future-scope)
* [Contributors](#contributors)
* [Mentors](#mentors)

## 🙂Introduction

### 🤔About Project
The project uses Blockchain Technology by implementation through Python and Flask in the backend for a server. It further uses SQL database for storing the user data such as password, username, email, account balance etc. Through HTML/CSS and JavaScript the Blockchain is deployed on a website. The website is on a local-host. This project enhances the knowledge of blockchain technology which has a very high potential in future.
<p align="center"><img src="https://user-images.githubusercontent.com/84843295/150372051-5301bfef-b50b-4a90-a5fc-6e2c0e876092.png" /></p>
<p align="center"><img src="https://user-images.githubusercontent.com/84843295/150372996-45c5f25e-5193-49f7-9898-7d45e418c357.png" /></p>


### ⚙️Tech-Stack
<p align="center">
<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png" alt="Python" height="40" style="vertical-align:top; margin:4px">
<img src="https://user-images.githubusercontent.com/84843295/146195365-6091ba76-93b5-45c2-967b-ae8831a501fa.png" alt="Java Script" height="40" style="vertical-align:top; margin:4px">
<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png" alt="css" height="40" style="vertical-align:top; margin:4px">
<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png" alt="html" height="40" style="vertical-align:top; margin:4px">
<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/flask/flask.png" alt="flask" height="40" style="vertical-align:top; margin:4px">
<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/visual-studio-code/visual-studio-code.png" alt="VS Code" height="40" style="vertical-align:top; margin:4px">
<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/mysql/mysql.png" alt="MySQL" height="40" style="vertical-align:top; margin:4px">
<img src="https://user-images.githubusercontent.com/84843295/146194516-a5a1dea3-b779-4a3f-8672-a02ead2267c6.png" alt="Block-Chain" height="40" style="vertical-align:top; margin:4px">
</p>

### 📁File Structure
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
## ⚒️Getting Started

### 😁Pre-requisites
The project involes the installation of following libraries and environment:
* Firstly obviously you should have [Python3](https://www.python.org/downloads/).
* Some basic libraries and frameworks will come pre-installed but you'll require MORE!!
* [Flask](https://flask.palletsprojects.com/en/2.0.x/): This the the framework that supports the website so installing this is a must else it'll throw ERRORS!!
* [Requests](https://pypi.org/project/requests/): This module is used only once :(, but none the less it is important.
* [An SQL connection with Flask](https://flask-mysqldb.readthedocs.io/en/latest/): This library ensures a connection between the MySQL Database and the Flask framework.
* wtforms: A python library used for getting inuput from a user in forms

Install all these requirements:
```
$ pip install -r requirements.txt
```
* After install Mysql on your PC open your prompt and type:
  ```
  $ mysql -u root -p
  ```
  and enter the password
* After follow thw following steps:
  ```
  $ CREATE DATABASE crypto;
  ```
  ```
  $ USE crypto;
  ```
  ```
  $ CREATE TABLE users(name varchar(50), email varchar(30), username varchar(30), password varchar(100));
  ```
  ```
  $ CREATE TABLE port5000(number varchar(10), hash varchar(64), previous varchar(64), sender varchar(30), recipient varchar(30, amount varchar(30), nonce varchar(20));
  ```
  ```
  $ CREATE TABLE port5001(number varchar(10), hash varchar(64), previous varchar(64), sender varchar(30), recipient varchar(30, amount varchar(30), nonce varchar(20));
  ```
  This is for 2 ports, for multiple ports make multiple tables and thus make changes in the list of connected tables in the app.py file accordingly
  
## 💻Usage
Assuming you have git, follow the following process
1. Clone the Git Repo:
   ```
   $ git clone https://github.com/AsRaNi1/R-Cell.git
   ```
2. Go into the Repo directory
   ```
   $ cd ../R-Cell
   ```
   
4. Run the `app.py` file in the directory with a port number
   ```
   $ python app.py 5000
   ```
5. Run `app.py` again but this time witha different port number, 5001
   ```
   $ python app.py 5001
   ```
7. 2 local-host server address will open on the 2 different terminals
   ![image](https://user-images.githubusercontent.com/84843295/150394240-fc791e9f-db2f-47c5-9364-36a116bae684.png)
   ![image](https://user-images.githubusercontent.com/84843295/150394392-72d2a8aa-5dc4-44a5-aa2a-44ff5773139b.png)
   
8. Register 2 accounts on the 2 different ports and thus there 2 ports become 2 different users. For more users make more tables and add them in the list of connected users in app.py

9. Now show this to your friends and boast about how you've created your own crypto-currency and that you're going to become a millionaire🤑


## 📷Glimpses
![image](https://user-images.githubusercontent.com/84843295/150394944-b4f875ae-2b7d-432b-ac1b-9a1e98277adb.png)

## Gdrive
[Drive Link](https://drive.google.com/drive/folders/1pRIjyaQoP_TqpbfkvwZpNw6Yk5XCMF5c?usp=sharing)


## 😵‍💫Trouble Shooting
The making of this project tackled numerous obstacles. Some were tricky, while some were very easy to solve.
1. The first problem faced was that the team was not working 🙂. This was the most tough and complex problem to solve since each member had to come out of their comfort zone and contribute.
2. **Installations**: The various modules to be installed keep getting updates regularly and so does their way of working, so managing to work with different versions of the same package/module was tricky indeed.
3. **Understanding**: Understanding Block-Chain, i.e getting its intuition at first was a bit difficult but eventually as we progressed the concept was well **inherited**.
4. **Programming**: Some of the members were seeing some new python syntax's and how to use the different modules.
5. **Debugging**: No comments.
6. **Choosing a good website design**: Choosing this was so tough that we try to keep adding new features regularly.
7. **Deploying the blockchain**: To deploy it on a server was not possible since blockchain is de-centralized, therefore for this SQL Tables were used for each user.


## 🔮Future Scope
Here are a few things we are planning on adding in the future
* Wallet
* mempools
* The webdev part requires a lot more efforts and we'll try and iumplement that throught react.js
## 👨‍💻Contributors
* [Arnav Zutshi](https://github.com/AsRaNi1)
* [Meloni Patel](https://github.com/meloni13)
* [Prathameya Walimbe](https://github.com/b0ngus)
* [Vedangi Patil](https://github.com/Veda-12)
## 🙏Mentors
A very special thanks to the mentors!!
* [Ravi Maurya](https://github.com/RaviMauryaHootowl)
* [Nikheel Indanoor](https://github.com/nikheelindanoor)
* [Shreyas Penkar](https://github.com/Shreyas-Penkar)
