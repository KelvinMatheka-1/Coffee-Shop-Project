# Authors
* Kelvin Matheka
* Gift Kipkemboi
* Gerald Kamau
* Maureen Murugi
* Mercy Chebet
# Table of contents
1. [Authors](#contributers)
2. [Description](#Description)
3. [Features](Features)
4. [Requirements](#Requirements)
5. [Installation process](#Installation)
6. [Technologies used](#Technologies)
7. [Live links](#Links)
8. [Contact Information](#COntact-Information)
9. [Licence Information](#License)
# Description
This web application allows a user to order coffee, by first signing-up, logging in, then choosing the coffee type they would love to purchase. THe application also allows users to leave reviews.
With React, there is an interface to select the coffee types, the coffee data is fetched from the local database.
By the use of rails, users sign-in, login, and order information is POSTed to the database, and GET the coffee data from the database.
With Active Record, a coffee has many users, a coffee has many reviews through users, a review belongs to a user, a  review belongs to coffee, and a user has many coffees and reviews are some of the associations in the web application.
# Features
As a user of the application, you will be able to;
1. Navigate through the application by first signing  uo and loggin in to place a coffee order.
2. A user can buy a coffee of choice and leave a review.
3. On the backend, rails sends the users info to the database and gets the coffee from the database.
# Requirements
User must have access to a computer.
User must be connected to the internet.
# Installation Process
Clone the repository: git clone 'https://github.com/KelvinMatheka-1/coffee-test'
Unzip the cloned files in a folder of choice.
# Technologies Used
1. Ruby on Rails - as the dynamic language to interact with ActiveRecords and backend.
2. React JS - Structure to the web application and interaction with the users.
3. SQlite3 - Interactions with the database.
# Live Front-end link
# Live Back-end link
# Authors Info
github:
'https://github.com/MaureenMurugi'
'https://github.com/KelvinMatheka-1'
'https://github.com/Gift-koech'
'https://github.com/MercyChebet'
'https://github.com/Gerald-ux-ux'
# License
MIT License
Copyright [2022][Group 7]
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.