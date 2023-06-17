
# Abstract

People's activity began to decline due to the presence of transportation, lack of movement, and
the large number of restaurants that serve unhealthy meals.
Our application is intended for the individuals who want to get a perfect body through healthy
food and exercises, and it is difficult for them to know what their needs and what suitable for them
hence the idea of our graduation project.
We developed mobile application which gives each individual the appropriate exercises for him
based on BMI calculations that depend on his age, weight and height, and the application also
provides suggestions for healthy foods and drinks.

The owner of our application could be a gym owner, so we developed an admin website admin
permission is to take food orders and add a coach, after coach is added, his permissions is to add
exercises, foods and drinks

A mobile application Frontend built in Flutter framework written in Dart, a website built in Flutter
framework also, for the back-end we used Node.js, with the MongoDB, and to send daily
reminders we used the Firebase database .



## Introduction
### Problem

Above all, our main goal was to define the main things we strive to put into our project.
When we chose healthy lifestyle subject, we initially understood the things that would be put
into the app to help administrators, coaches, and users. Of course, this was only the beginning,
our initial steps were research, and upon research we noticed that the main problem was the
lack of commitment of the participants to go to the gym. As for some circumstances that may
happen to them, or if they are lazy, they seem to resent this situation, and our project has helped
them use it at home.
### Objectives
Our goal is to create a program that helps subscribers in the gym to do exercises, whether at
home or in the club, and it is flexible in terms of dealing with it, and it also helps the person to
collect data about his weight and give him a chart that shows his weight tracking, and his
progress over a period of time, it helps the user to choose to order a healthy food/drink from
suggested ones ,and he could calculate if the calories suitable for him or not , and here is our
project that meets these needs.

### Project scope
We dealt and focused in our project on gym owners, coaches and participants as well, and we
understood the nature of their work in the gym, their permissions, services available to them and
it developed according to the environment used, home or gym, we researched and took all the
ideas.
### Importance
Our project contributes many advantages. A person calculates their body mass index (BMI) by
entering their weight, height, and age. Accordingly, an overweight, a underweight, or an ideal
weight appears, and then suitable exercises are offered to him based on the BMI, a chart will be
given to let him tracking his weight, the other advantage of our app ,it will show healthy foods
and drinks with feature of entering ingredients that he is allergic from it , so the food/drinks that
contain this ingredients will be hidden, other feature he can order food and drink in different
quantities, then he could calculate if the calories he ordered meets his daily need or not, if the
orders are higher than what is allowed per day, he will be given a pop up screen suggests to delete
one of them. Another advantage he can add an alarm which reminds him of the sport time given
by him.

### Constraints
During the course of working on the project, we encountered several difficulties, including:
1- The first difficulty was the incompatibility of the versions with each other, and this causes many
problems.
2- All the techniques and languages used were self-learning during this period, which required
learning and applying at the same time.
3- But the hardest thing was to find the learning resources which were evident in the combination
of Flutter, NodeJS and Mongo DB Atlas. Which required more time and effort.
### Standards
MVC (Model View Controller)
The controller style has been used to display the form in our system. we can
Divide the entire project into three phases to make it easier to follow the work flow. These
components are as follows:
1. Model: represents the database we used, Mongo DB. It will respond to both the view request
and the console request to continue updating itself.
2. Presentation (view): It represents the graphical user interface GUI for subscribers to enjoy the
available services, the GUI that the coach and admin will use to add or delete food/drinks and to
add coaches or take orders.
3. Controller: It represents the back-end server built with NodeJS, which facilitates coordination
and collaboration between Model and View. It is also responsible for managing the logic of the
application.
Earlier Coursework
Regarding the online course, the Flutter and Node JS course was taken and used to build the
project, as well as the critical thinking skills course which helped us to write this report.



### Implementation
We developed a mobile application that aims to solve the previous problem, as it contains
many features, the most important of which are: an application that combines exercise and
healthy food, in addition to calculate the body mass index and also to calculate the calories
suitable for you per day and to order food accordingly, in addition we developed an alarm for
reminders, and the body weight tracking chart.

## Project Design: Admin Website
### Sign in
Now we will display the admin website with all its pages and a brief explanation of it.
![1 jpg](https://github.com/saharSaleh22/Software_GP_Demo/assets/78207579/90257c92-4095-4611-9c52-1fea4124bd93)

This is the login page for the website, in this page the admin should enter his credentials then he
will enter the home admin page, if the user checked the coach login box, then he will enter the
coach home page.
![2 jpg](https://github.com/saharSaleh22/Software_GP_WEB_Demo/assets/78207579/47ea0c91-4aa9-4ff8-b6da-2eaab9783429)
   This is the admin home page, you can see there is a list, that admin have access to them, we will explain more in the next page.
   ![3 jpg](https://github.com/saharSaleh22/Software_GP_WEB_Demo/assets/78207579/800b40e2-f20c-4274-b941-2b6c833ad071)

   The first page of admin list that he could see the all food types added to the mobile app by the coach , he can switch to drink or meal using “table of: “ list .
  ![4 jpg](https://github.com/saharSaleh22/Software_GP_WEB_Demo/assets/78207579/387028f4-ad0b-4c3a-9ead-2f5d151f8b79)
 The second page of admin list that he could see the all Exercises added to the mobile app by the coach, he can switch to other exercises group using “table of: “ list .
 ![5 jpg](https://github.com/saharSaleh22/Software_GP_WEB_Demo/assets/78207579/d980ec05-3bc9-412c-8cd1-192559b1e5e2)
  The third page of admin list that he could see the all orders for foods from the app users and he can delete an order if he want.
  ![6 jpg](https://github.com/saharSaleh22/Software_GP_WEB_Demo/assets/78207579/f7222c37-d4b7-4374-a745-a1c2926544b2)
In this page the admin can add a coach, and he can fill some data for him.
Also, there is a page to sow all coach’s data, and he can delete any of them.
![7 jpg](https://github.com/saharSaleh22/Software_GP_WEB_Demo/assets/78207579/50f51021-b925-4858-9a15-7065e3272188)

  If he checked the coach login check box, then he will enter this is coach home page. Which enables him to do a list of features as: add food (meal or drink), add exercises (depend on area of focus) And to show the tables for food or exercises and throw them he can delete a food or exercise if he wants.
  ![8 jpg](https://github.com/saharSaleh22/Software_GP_WEB_Demo/assets/78207579/87961468-a220-4aec-967f-414d305f9e63)
In this page the coach can add a new meal or drink depends of what he selected from the list , he can add the food name , calories count , price , making time , ingredients, recipe , difficulty level an photo of the drink or meal .
![9 jpg](https://github.com/saharSaleh22/Software_GP_WEB_Demo/assets/78207579/879288b6-5b60-4103-80ed-e7af9d107f65)
Here the coach can add a new exercise depends on the area of focus  list as  shown in the Figure  above. He will add exercise name, repeat count, a gif for the exercise and a video .
![10 jpg](https://github.com/saharSaleh22/Software_GP_WEB_Demo/assets/78207579/8814af4f-6514-4fa7-bbf6-e3919cd2994d)
Here we chose another area of focus from the list and the page content will change as you can see in the figure above.

## Demo Link
-[admin web demo link](https://drive.google.com/file/d/1pF6P3yFbpWl9sFAHwQvrpRA7tFdVjMM9/view?usp=sharing)
## Authors

- [@saharSaleh22](https://www.github.com/saharSaleh22)

