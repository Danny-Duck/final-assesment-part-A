# Purpose

The Purpose of our app is to create a platform for small restaurant owners to establish an online presence.

With "final project name" the restaurant owner will be able to create a simple page with general information about their business to have a google page ranking.

Currently the skew of restaurant online representation is large and confusing. Some opt for just a google maps listing, having only opening hours, address and contact information. Others options are a facebook page, which offers less customisation, or a full fledges wix website which can be time consuming and confusing.

We aim to solve this problem of multiple identities, where businesses can collected all their information in one place, while linking already established identities, such as Instagram, UberEats and or Google Maps.

# Features/Functionality

The final application should have the following features

- Account registration - User should be able to sign up for a new account
- Log in functionality - Registered User should be able to log in to their accounts
- Create a restaurant web page - A user should be able to create and add a new restaurant page
- Create/Add a menu to a restaurant - Users should have the ability to add one or more menus to their restaurants
- Create/Add items to menus - Users should be able to add items to their menus
- Tag items - Items should be able to have one or several different tags such as dietary information like vegan, gluten free etc.
- Add ingredients to items - A user should be able to add ingredients to their items
- Different sizes or prices - A user should be able to have different sizes of item that can have different prices. For examples glass of wine or bottle of wine.
- Pick different themes for menus and items - Users should be able to pick different layouts/themes for their menus and items
- Pick different colours and styles for restaurant, menus and items - A user should be able to customize the colours, fonts and styles of their restaurant page, menu sections and each item in their menus.
- Add extra contact information - A user should be able to add additional information about their restaurant such as google maps link, phone number, social media or delivery service.
- Edit their webpage - Users should be able to edit their restaurant web page including themes, styles and information.
- Unique URLs - Restaurants should have unique web urls
- View their webpage - Anybody should be able to view the restaurants webpage

# Target Audience

The target audience for this project is aimed specifically at small restaurant owners who may not have their own website or web presence. This service is to give those small business owner an opportunity to have an customizable webpage to show case their restaurant. This site could also be suitable for larger restaurant owners who want a quick and easy way to get some online presence without having to build their own website.

It will also target everyday restaurants customer who are looking for more information about local smaller restaurants online and want to see their menu offerings as well as filter through their menu depending on different criteria.

# Tech Stack

Backend Language/Framework

- Ruby on Rails

Front End Framework

- React
- CSS/SASS

Database

- PostgreSQL

Image Storage

- AWS S3 Buckets

External APIs

- Stripe

Version Control/Repo Hosting

- Git/Github

Deployment Services

- Heroku
- Netlify

# User Stories

## Restaurant Owners

My name is Jimmy Hendrix, I own a small juice bar called Jacked Juice. I wish to establish an online presence but don’t have the time or money to set up a complete website.

- I want to create an account. Fill out information about the items on my menu
- I want to have a site generated for my restaurant displaying opening hours and street address.
- I also want to have a link to my Instagram on the site.

My name is Elon Tusk, I manage a small burger chain, each shop has a different menu. I already have an account with “final project name".

- I want to update opening hours of a restaurant
- I want to add a new item to a menu.

My name is Al Capone, I help out at my parents restaurant. They have a Hawaiian lunch and Italian dinner menu as well as a drinks and happy hour menu.

- I want to create multiple menus
- I want to have a theme each of them.

My name is Dandrews, I run a small food truck. I don’t have the means to set up a complete website.

- I want to create a “final project name” site.
- I want it to display the hours I operate
- I want to list the multiple locations I operate my truck from
- I also want to list the food available.

## Customers

My name is Angela Merkel, I’ve come to a new area of my city and am craving banana cake. After googling local bakeries I find a “final project name” site on here;

- I want to search the menu for banana bread,
- I want to find opening hours and a phone number.
- I want to enjoy cake

My name is Austin Powers, I have a favourite restaurant in my town and I wish to know more about their menu and the gluten free options available. I visit their “final project name” site on here;

- I want to organise the menu prioritising gluten free.
- I want to see what items they deliver

My name is The Zuck, I want to find out what my local Chilean restaurant offers for take away and their phone number. I google Chilean food and find a "final project name" listing on here;

- I also want to find their vegan options available for takeaway.
- I want to find their UberEats Account

# Dataflow Diagram

![Dataflow Diagram](./resources/DatafFlowDiagram.png)

# Entity Relationship Diagram

![ERD](./resources/ERD.png)

# Application Architecture Diagram

![Application Architecture Diagram](./resources/AppArchitectureDiagram.png)

# Wire Frames

Below are the wire frames for this project, to better understand them the following legend has been provided.

![Wire Frame Legend](./resources/wireframes/mobile/Legend.png)

As shown on the legend above image place holder are represented by large grey square, user input by grey rectangles with text and button by blue rounded rectangles.

## Mobile

### Landing Page

![Landing Page](./resources/wireframes/mobile/Landing.png)

The landing page will have a large image as a background.

### Log In

![Login](./resources/wireframes/mobile/Login.png)

### Sign Up

![Sign Up](./resources/wireframes/mobile/CreateAccount.png)

### Update Account

![Update Account](./resources/wireframes/mobile/UpdateAccount.png)

### User DashBoard

![Account](./resources/wireframes/mobile/Account.png)

Clicking the edit button will allow a user to change their password, name and email.

### Restaurant Creation

![Create Restaurant](./resources/wireframes/mobile/CreateRestaurant.png)

Clicking add for opening hours and contact details will add a form below each section respectively to allow for a user to fill in and add a new entry.

Clicking the colours in the colour scheme will open a colour selector in which a user could select a colour.

Filling in the text input labelled "Enter Menu Name" and pressing Add a Menu will add a new Menu.

### Menu Theme Selection

![Pick Menu Theme](./resources/wireframes/mobile/PickMenuTheme.png)

Clicking the colours in the colour scheme will open a colour selector in which a user could select a colour.

### Item Theme Selection

![Pick Item Theme](./resources/wireframes/mobile/PickItemTheme.png)

Clicking the colours in the colour scheme will open a colour selector in which a user could select a colour.

### Menu Item 

![Add Item](./resources/wireframes/mobile/AddItem.png)

Pressing the grey image box below will allow you to upload an image.

### Menu View 

This wire frame shows how the menu might look like on a final page restaurant page.

![Menu View](./resources/wireframes/mobile/MenuView.png)

### Tag Filter Selection

The following wire frames shows how filtering of tags might work on a final page.

![Filter Options Menu](./resources/wireframes/mobile/FilterOptionsMenu.png)

![Filter Options Menu 2](./resources/wireframes/mobile/FilterOptionsMenu-1.png)

## Desktop

### Landing Page

![Landing Page](./resources/wireframes/desktop/Landing.png)

The landing page will have a large image as a background.

### Log In

![Login](./resources/wireframes/desktop/LogIn.png)

### Sign Up

![Create Account](./resources/wireframes/desktop/CreateAccount.png)

### User DashBoard

![User Dashboard](resources/wireframes/desktop/UserDashboard.png)

Clicking the edit button will allow a user to change their password, name and email.

The grey image box will show a preview of the website.

Clicking add for opening hours and contact details will add a form below each section respectively to allow for a user to fill in and add a new entry.

### Restaurant Creation

![Create a restaurant](./resources/wireframes/desktop/CreateARestaurant.png)

Clicking add for opening hours and contact details will add a form below each section respectively to allow for a user to fill in and add a new entry.

Clicking the colours in the colour scheme will open a colour selector in which a user could select a colour.

Filling in the text input labelled "Enter Menu Name" and pressing Add a Menu will add a new Menu.

### Item Page

![Item Page](./resources/wireframes/desktop/ItemPage.png)

Pressing the grey image box below will allow you to upload an image.

## Theme Selection

![Theme Selection](resources/wireframes/desktop/StylePage.png)

Clicking the colours in the colour scheme will open a colour selector in which a user could select a colour.

The images will give you a preview of the themes chosen.

### Restaurant Edit View

![Restaurant Edit View](./resources/wireframes/desktop/RestaurantEditView.png)

In this view you should be able to press an item/menu/the restaurant to get a colour selector to choose some of the colours. Clicking any of the edit icon will bring you to the appropriate pages for editing.

### Restaurant View

![Restaurant View](./resources/wireframes/desktop/RestaurantView.png)

This is what a final page restaurant may look like on desktop.

## Custom Templates

Restaurant owners will be given three templates for their menus and menu items below are the wire frames that outline how these would look like both on mobile and desktop.

### Menu Templates

#### Menu Template 1

![Menu Template 1](resources/wireframes/desktop/MenuTemplate1.png)

![Menu Template 1](resources/wireframes/mobile/MenuTemplate1.png)

#### Menu Template 2

![Menu Template 2](resources/wireframes/desktop/MenuTemplate2.png)

![Menu Template 2](resources/wireframes/mobile/MenuTemplate2.png)

#### Menu Template 3

![Menu Template 3](resources/wireframes/desktop/MenuTemplate3.png)

![Menu Template 3](resources/wireframes/mobile/MenuTemplate3.png)

### Item Templates

Items template will look the same on both desktop and mobile

#### Item Template 1

![Item Template 1](./resources/wireframes/desktop/ItemTemplate1.png)

#### Item Template 2

![Item Template 2](./resources/wireframes/desktop/ItemTemplate2.png)

#### Item Template 3

![Item Template 3](./resources/wireframes/desktop/ItemTemplate3.png)

### Final Template

This is what a web page may look like both on mobile and desktop after these templates has been applied.

![Restaurant Mobile Template](resources/wireframes/mobile/RestaurantTemplate.png)

![Restaurant Desktop Template](resources/wireframes/mobile/Desktop-1.png)

# Task Management

To organise and manage task we will be using Trello. Trello will allow us to track the task which each team members are working on as well as track the task status. The way our task workflow would work is, a new task will first be created in the to do list at which point it will be labelled by the different labels explained here:

- Code - This specify a task required coding
- Structure - This task involved adding or structuring the code or project, often involving command lines.
- Design - This task involves anything to do with aesthetics of the project
- Project Management - A PM task often involves documentation or the management of the project
- Bug - This specifies a task that involved fixing a problem or error
- Testing - This task involves creating tests.

We will also assign a due date and any other relevant information to each card. When we start working on a task we will assign ourselves to the task and move it to the doing list. Once a task is completed if it is a code task we move it to the testing list to go through testing. After the task has been tested or if its a non-code task a task will be moved to review where the task will be reviewed by another team member before being moved to Done. Review is also where any code refactoring will be done. Tasks can be moved back and forth between the list depending on if more work needs to be done on them or if tests fails. The following screenshots are screenshots of the Trello board for each day since the project start.

## Tuesday 14-07-2020

![Day 1 Trello](./resources/trello/Screenshot_2020-07-14%20T3A2%20-%20Final%20Project%20Trello.jpg)

## Wednesday 15-07-2020

![Day 2 Trello](./resources/trello/Screenshot_2020-07-15%20T3A2%20-%20Final%20Project%20Trello.jpg)

## Thursday 16-07-2020

![Day 3 Trello](./resources/trello/Screenshot_2020-07-16%20T3A2%20-%20Final%20Project%20Trello.jpg)

## Friday 17-07-2020

![Day 4 Trello](./resources/trello/Screenshot_2020-07-17%20T3A2%20-%20Final%20Project%20Trello.jpg)

## Saturday 18-07-2020

![Day 5 Trello](./resources/trello/Screenshot_2020-07-18%20T3A2%20-%20Final%20Project%20Trello.jpg)

## Sunday 19-07-2020

![Day 6 Trello](./resources/trello/Screenshot_2020-07-19%20T3A2%20-%20Final%20Project%20Trello.jpg)