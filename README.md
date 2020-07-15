## Purpose

Hidden Gems is an application for mapping and exploring interesting places. It aims to create an interactive, easy to use database of interesting, unique and free places to explore, which are created by the users. Places could include historical landmarks, photography locations, street art, natural wonders or any place of interest that is free and publicly accessible.

Hidden Gems is different from other travel/activity finder apps is that it is purely focused on showing free, outdoor places of interest rather than commercial establishments, and tourist attractions, and it aims to utilise the knowledge of users to uncover lesser known unique and interesting places.

We are aiming to serve a community of people who are looking to explore, travel and share their favorite places with anyone who wants to discover them.

## Functionality & Features

User Authentication

Interactive Map
- The main page of the app will include an interactive map
- A search bar, allowing users to search places by location
- Search filters so users can search by category or rating
- Clickable markers for each place on the map

Show Page
- Each location will have it's own page that shows details about the location, comments and an image gallery

Create, Edit and Delete locations
- Users are able to create, edit and delete locations
- Users can pin the location they want to add on a map, using a draggable marker
- Users can edit and delete the locations that they have created
- Admin users can delete any location

Image Uploads
- Users upload an image when they create a location
- Users can upload images to any location which will be displayed in it's image gallery

Comments
- Users can leave comments on each location

Rating
- Users can rate a location

## Target audience

Due to the flexibility in terms of the types of locations that can be added to the application, this app will serve many different users with many different interests.

There is the potential to evolve with the users who upload locations and interact with the app, as popular locations are prioritised in search results and different categories can be added to meet user demand.

Initially, we will focus on a few different interest groups that we believe will benefit from using this app.

**Tourists/Travellers**
This app could be a useful tool for tourists to easily find interesting sights and places of interest, wherever they are travelling

**Creative Types**
This could include artists, arts and architecture enthusiasts who want to explore art around the city

**Photographers/Photography Enthusiasts**
Photographers can use the app to find locations that are good for photography, while utilising the locations image gallery to get an idea of the types of photos that can be taken

## Tech stack

Backend Language/Framework
- Ruby on Rails

Front End Framework
- React

Database
- Postgresql

Image Storage
- AWS S3 Buckets

Version Control & Repository Hosting
- Git/Github

Deployment Services
- Heroku
- Netlify

## User Stories

***Meghan is a photography student who is completing a project on architectural photography.***

As a user, she will need to be able to sign up and log in to the site so that she can save and view locations later. 

She also wants to search for locations in her city where she can take interesting photographs for her project. Before deciding where to go, she would like to view photos uploaded by other users in different locations in order to make a decision.

***Tim is taking a year off uni to travel around the world. He is travelling on a budget and is always looking for free and interesting places to explore, wherever he travels.***

As a user, Tim wants to see all the interesting locations on the map which is near where he stays, and easily click on locations to decide what places to visit.

As a contributor, Tim would also like to leave comments and ratings about the places he visited, to help fellow travellers find the best places to visit.

***Todd is an enthusiast for street art. He wants a way to share the locations of interesting street art in his city, so that other people can more easily find and appreciate it.***

As a user, he wants to be able to pin-point locations of good street art on a map and add them so that other people can easily find them, without having to know their address. 

Todd recently received a comment on one of his locations explaining that the address was incorrect. As a user, he wants to be able to edit the location to correct the error.

***Candace is a travel blogger and social media influencer who is looking for ways to gain more exposure.***

As a contributor, she wants to be able to upload photos to locations on the app, by linking her instagram account to the app, in order to direct potential followers to her profile.

***Tess is an admin for Hidden Gems.***

She has noticed that sometimes people add locations that are spam, advertisements or just irrelevant to the site. She needs to be able to delete these locations so that they don't clog the site and make it harder for users to find what they are looking for. She also needs to be able to delete comments on locations for the same reasons.

>I initially was going to have one user story for each target audience, but then I realised this alone did not cover all the features of the application. I made sure to include user stories that referred to features such as adding a location and uploading photos to a location and then later added the admin user to explain cases where locations might need to be deleted.
>--- *Tess*

![Whiteboard - User stories](./docs/userstories.png)

## Dataflow Diagram

![Dataflow Diagram](./docs/dataflow-diagram.png)

## Application Architecture Diagram


![Application Architecture Diagram](./docs/application-architecture-diagram.png)

## Wireframes

### Landing Page
**Compress icon** in the search bar initislises using current location in the browser and to generate an address for search.
**Search bar** Once address is entered, it will prompt user to the **Main page** of the application.

*Desktop*
![Landing Page](./docs/wireframes/landingpage_desktop.png)

*Mobile*
![Landing Page](./docs/wireframes/landingpage_mobile.png)

### Main Page
The interfaces of the main page and "dashboard" page are very similar. The only different is that the "dashboard" page will be displaying locations created by the user and saved locations instead of nearby locations.

*Add a location* in navbar create a link for user to get to the **Add location** page.
**Interactive map with markers** allows users to access the specific **location page** while its link is also integrated with the list on the right side scrollable panel.
**Hide button** to enhance users' visual experience, filter panel will be minimised on click and the map area will be expanded.

*Desktop*
![Main Page](./docs/wireframes/mainpage_desktop.png)

**Toggle button** in the mobile view allows users to switch between the map layout and the list layout of the list of locations.
**Filter button** is to compensate the lack of space in the mobile view. Filter options are not displayed in mobile view but can be accessed by clicking the filter button.

*Mobile*
![Main Page](./docs/wireframes/mainpage_mobile.png)

### Add Location Page (Edit page)
The layout of the add location page will be shared with edit page.

Once the form is completed and submitted, it will redirect users to the location page which they just added/edited.

**Marker in map** in the desktop view can be used for generating address instead of manual input in form.

*Desktop*
![Add Location Page](./docs/wireframes/addlocation_desktop.png)

*Mobile*
![Add Location Page](./docs/wireframes/addlocation_mobile.png)

#### Location Page
**Check-in button**
- Desktop view - prompts an on screen window for recording rating, comments and date etc
- Mobile view - redirects users to the rating page to record the same information


Then, it returns users back to the location page on submission.

![Location Page](./docs/wireframes/locationpage_desktop1.png)

![Location Page](./docs/wireframes/locationpage_desktop2.png)


*Desktop*
![Location Page](./docs/wireframes/locationpage_desktop1.png)
![Location Page](./docs/wireframes/locationpage_desktop2.png)


*Mobile*

![Location Page](./docs/wireframes/locationpage_mobile.png)

Project Management
---

Trello

Trello is a project management application used to plan and track the progress of different tasks. We will be using Trello to manage and track tasks throughout the project.

![Trello Board](./docs/trello/trello3.png)

![Trello Board](./docs/trello/trello4.png)

![Trello Board](./docs/trello/trello1.png)

![Trello Board](./docs/trello/trello2.png)

Miro

Miro is a digital whiteboard used for planning, brainstorming and idea generation. We will use this tool to collaborate on ideas throughout the project. 

![Miro Board](./docs/trello/miro.png)
