# Finding-missing-person
## Project Implementation
**1. Registering New Cases**

The first step is to register a new case. The GUI application is built using PyQT5 that allows you to collect all relevant information and store it in database Postgres

![image](https://user-images.githubusercontent.com/105723816/170830275-c7027cf3-5975-4f3f-8868-972c7583fdcd.png)


**2. Waiting for Users to submit images**

The common people will use an application on their mobile to submit photos of people who they think have lost or found begging while keeping them their identity anonymous.and then we match those with registered cases.

![image](https://user-images.githubusercontent.com/105723816/170830241-64fa5aa8-778c-46e1-a7ba-08f4de95c5b4.png)

**3. Matching Cases**

 We use  **KNN Algorithm** to match the case images and user submitted images.
 
 ![image](https://user-images.githubusercontent.com/105723816/170830428-d53c9aa3-6e66-4309-9b6e-b12b76de9746.png)


## HOW TO RUN
**With Docker**

Prerequisites

$ git clone git@github.com:harshi-21/Finding-missing-person.git

$ cd Finding-missing-person

$ docker-compose up --build

$ cd app

$ pip install -r requirements.txt --no-cache-dir

$ python3 login_window.py
 
 **At this point you'll see a window like this Login Window**
 
![image](https://user-images.githubusercontent.com/105723816/170830623-2a7a3801-1ba5-46c9-8d30-8ddc5d1584b4.png)

Default username: admin Default password: admin

After logging in you'll see the main screen through which you'll be able to submit cases.

 
**To run the mobile application:**

$ cd mobile_app

$ python ui.py

After that you'll see a window like this

![image](https://user-images.githubusercontent.com/105723816/170830738-b9c8e813-0e7f-4cec-ab64-379df91a7302.png)



 
