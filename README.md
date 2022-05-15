# PePeps

## Summary
- [Introduction](#introduction)
- [Distinctiveness and Complexity](#distinctiveness-and-complexity)
- [Requirements](#requirements)

## Introduction
I started my journey with the CS50's Web course as a undergraduate student. It was the first course I took outside the university and made me learn a lot within a very short time. I managed to deliver every previous project within 6 months, from June to December, however after I landed my first internship in January (in many ways thanks to the knowledge I achieved with this course) and with the final semesters of my undergraduate course upon me, I struggled to finish the final project. Now, more than a year later, here I am with an idea I believe can finally make me finish this course with pride!

The idea for this project is to create a website that centralizes common needs that pet's owners face on a daily basis, such as:

- find a trustworthy place to leave their pet;
- find information about pet's health and what to do in face of a situation;
- schedule a visit to the vet;
- buy products (food, snacks, clothes, accessories, etc) and have them delivered to your home;
- keep the pet's vaccines and other information up to date;

All of these ideas came from the numerous experiences me and my girlfriend faced when raising our dog, our Baby Boy: Nugget.

<img src='' alt='Nugget'>

## Distinctiveness and Complexity

<!--  
It reaches new levels of:
- frontend organization (html, css and js folder structure)
- mobile responsiveness
- ui/ux design - to be more professional (even including js plugins for more dynamism)
- backend organization (views.py as a views folder)
- unit and integration tests
- devops (possible to run with docker to ease the installation process)
-->

## Requirements
The requirements listed below is a filtered list from many many ideas, that should suffice the scope of this project.

- **Users**: Users will have to pick from 2 different profiles: Enterprise or Home.
  - Enterprise users will be able to: have many stores, each store will have to mark at least one out of the 3 services: petstore, veterinary clinic and hotel.
  - Home users will be able to: buy products, require services (detailed below) from the petstores available, announce themselves as Pet Sitters, create a registration for each of their pets.
- **Stores Page**: Page that displays all the stores.
  - Users should be able to filter stores by their company, location (country, state and city) and services available.
- **Pet Hotels Page**: Page that displays pet hotels options.
  - Every option should have, in it's own page: a name, description, contact information, payment methods accepted, at least 3 photos of the place and one of the host, ratings (1-5 stars) and commentaries left by previous clients.
  - Users should be able to filter out stores based on their rating and available schedule.
  - After the user chooses a place, they should be able to schedule a visit if they like, or just schedule the period the pet is gonna stay (maximum period of one month).
  - After that, the user has to describe the reason for leaving their dog and choose a payment method.
  - Users should be able to see how is the schedule through a calendar.
- **Pet Products Page**: This page displays all products from every petstore.
  - Every product should have a name, description, 3 to 5 photos, price, 1-5 stars rating, questions section, related products listed next to it.
  - Users should be able to filter out products based on their rating and number of sold units.
- **Veterinary Clinic Page**: Page where the user can schedule veterinary consultations, buy medicine and them delivered.
- **Enterprise Page**: Page that displays the name, description, logo of the company; and a summary of all the services it provides.
  - Every service should be clickable and redirect the user to the service's page (pet hotel, petstore or veterinary clinic).
- **Pet Sitter Page**: Page where all the information of the user as a pet sitter will be displayed.
  - This page must contain the sitter's: name, address, age, 3 to 5 photos, description of it' experience with pets, schedule available, history with previous pets.
  - A pet sitting should be added to the sitter's history after it's conclusion. The pet sitting is concluded after the user gets his/her pet back and hit the conclusion button of the sitting page.
  - Every user should be able to check a list of it's active hired pet sitters.
  - Every user should be able to check a list of it's previous hired pet sitters.
