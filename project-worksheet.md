# Project Overview

## Project Schedule

This schedule will be used to keep track of your progress throughout the week and align with our expectations.  

You are **responsible** for scheduling time with your squad to seek approval for each deliverable by the end of the corresponding day, excluding `Saturday` and `Sunday`.

|  Day | Deliverable | Status
|---|---| ---|
|Day 1| Design Mockup for Website in all views | Complete
|Day 1| Documentation | Complete
|Day 2| Project Approval / Initial Design | Complete
|Day 3| Revisions/Changes and Javascript | Complete
|Day 4| Revisions/Changes and Javscript | Complete
|Day 5| Final Touches | Complete
|Day 6| Present | Complete


## Project Description

Portfolio by Sometimes is an extension of my brand "..by Sometimes," with the parent being Designs by Sometimes. I wanted to make something simple, responsive and modern looking that would be a great starting point for me to build on as I progress as a developer. I went with a block layout and a color palette that would suit my style. It's clear, concise and to the point with a subtle nod to where I'm based out of. I want to throw in this [portfolio](https://www.ktumangan.com/) I came across on here because it was one of my favorite ones and it was my main inspiration for my page layout because of the 10-15 portfolios I looked at that was the one that I kept taking a second look at and felt the most "me" naturally.

## Google Sheet

Here is my: [Google Sheet](https://docs.google.com/spreadsheets/d/e/2PACX-1vRTjcaVEgEjRmpg1J-xK2eK5xfQ4Vjw0ZEpYctzo2PkOHHzbOa6hfwb6508OEX3g208s85es822igok/pubhtml) 

## Wireframes

This is the mobile render of my website mockup:

![](https://i.imgur.com/7TqK5iO.jpg)

This is the desktop render of my website mockup:

![](https://i.imgur.com/PXdYNBd.jpg)

## Time/Priority Matrix 

Here is my time/priority matrix:

![](https://i.imgur.com/siqDKF6.jpg)

The way that I setup my time/priority matrix I wanted to work on the the layout/design elements with HTML/CSS first because that is something I feel more comfortable doing at this point and I didn't want to spend extra time struggling right out of the gate when I could get a lot more done and sooner and have more time to work on functionality.

My Portfolio To-Do List:
-Mockup and documentation.
-Designing the page layout with containers.
-Adding specific elements to each container, such as the contact form or background image.
-Adding functionality via JSON and the Google Spreadsheet we made in class.
-Finishing styling touches and making sure that elements are where I want and in the correct place.


### MVP/PostMVP - 5min

The functionality will then be divided into two separate lists: MPV and PostMVP.  Carefully decided what is placed into your MVP as the client will expect this functionality to be implemented upon project completion.  

#### MVP (examples)

- Pull data using google json api
- Render data on page 
- Allow user to choose favorites 
- Save their choices in firebase

#### PostMVP 

- Anything else that is not MVP

## Functional Components

Based on the initial logic defined in the previous sections try and breakdown the logic further into functional components, and by that we mean functions.  Try and capture what logic would need to be defined if the game was broken down into the following categories.

Time frames are also key in the development cycle.  You have limited time to code all phases of the game.  Your estimates can then be used to evalute game possibilities based on time needed and the actual time you have before game must be submitted. It's always best to pad the time by a few hours so that you account for the unknown so add and additional hour or two to each component to play it safe.

#### MVP
| Component | Priority | Estimated Time | Actual Time |
| --- | :---: |  :---: | :---: | 
| Mockup | H | 2hr | 2hr |
| Documentation | H | 2hr | 2hr |
| Page Layout | H | 3hr | 3hr |
| Hamburger | H | 2hr | 2hr |  
| CSS Grid/Flexbox | H | 3hr|  4hr | 
| Bootstrap | H | 2hr | 2hr|
| Javscript | H | 4hrs|  4hr | 
| Wishlist Items | H | 2hr | 2hr |
| Finalizing Page | H | 2hr | 2 hr |
| Total | H | 22 hrs| 23 hrs |

#### PostMVP

| Component | Priority | Estimated Time | Actual Time |
| --- | :---: |  :---: | :---: | 
| Mockup | H | 2hr | 2hr |
| Documentation | H | 2hr | 2hr |
| Page Layout | H | 3hr | 3hr |
| Hamburger | H | 2hr | 2hr |  
| CSS Grid/Flexbox | H | 3hr|  4hr | 
| Bootstrap | H | 2hr | 2hr|
| Javscript | H | 4hrs|  4hr | 
| Wishlist Items | H | 2hr | 2hr |
| Finalizing Page | H | 2hr | 2 hr |
| Total | H | 22 hrs| 23 hrs |

## Additional Libraries
 Utilized W3Schools, Bootstrap, Stack Overflow, CSS Tricks, Font Awesome, Markdown Lesson.

## Code Snippet

The code snippet that I provided was center piece of my portfolio page in my opinion and I really like how it turned out despite being something so simple. Rule #32: Enjoy the little things.

```
  <div class="brandStatement">

    <div class="brandText">
          <p id="hello">Hello, my name is...</p>
          <p id="myName">Gore Sometimes</p>
          <p id="designer">I'm a designer specializing in modern UI and visual design.</p>   
      </div>
  </div>

    .brandStatement {
        background-image: url("https://i.imgur.com/LLLE3mL.jpg");
        background-size: cover;
        background-position: 0px;
        margin: 10px;
        height: 400px;
        display: flex;
        justify-content: center;
    }

```

## Issues and Resolutions
 My biggest issue was linking my Google Spreadsheet to the cards on my page. It took me longer than I would have liked but I'm grateful for my classmates who helped me troubleshoot. The issue initially was that the ajax was pulling it's data from my index.html page and console logging that. It then turned to logging the correct data but giving me errors of variables not being defined or a jquery error message. The resolution came in the form of renaming variables and making sure that ${project.(element)} were in all the correct places and some formatting that was off. Glad to have gotten it done and a huge shoutout to Sampreet and Allisyn for helping me through it.
