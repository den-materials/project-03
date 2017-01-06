# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png" height="60"> Project 3 - SEAN Group Project

**Read this entire document before writing a line of code.**

## Contents

* **[Overview](#overview):** What is this project?
* **[Planning & Deliverables](#planning--deliverables):** What will we be turning in?
* **[Technical Requirements](#technical-requirements):** What technologies will we be using?
* **[Further Exploration](#further-exploration):** What if we want to do more?
* **[Deadlines](#deadlines):** When is it due?
* **[Submission](#submission):** How do we turn in the project?
* **[Project Groups](#project-groups):** Who are my group members and assigned instructor?
* **[Presentation Guidelines](#presentation-guidelines):** What should we cover during our presentation?

---

## Overview

###### What is this project?

For the third project, you will use your knowledge of front-end and back-end web development to produce a polished web application that can be used by friends, family, or the wider online community -- and that will benefit your portfolio.

**The objective of this project is to:**

* Work with a group in a shared GitHub repository.
* Plan and implement a larger scale project as part of a development team.
* Integrate topics learned and experience gained in the course so far.
* Showcase your abilities to potential employers, friends, family, and community members.
* Create a product that serves a well-researched user need

**You will be working in groups of 3 or 4 for this project.**

---

## Planning & Deliverables

###### What will we be turning in?

### Project Planning Deliverables

**You must review the following with your instructional team BEFORE lunch next Friday.**

* **Scope:** What are you planning to build? What do you reasonably think you can implement in the time period?
* **User Stories:** Who is your user? What features will your app have? Set up your project and user stories in <a href="https://trello.com" target="_blank">Trello</a> or in some other organized format.
* **Wireframes:** Sketch out what your core pages will look like and how they will work. Consider making a *paper prototype* to demonstrate and/or test key user interactions.
* **Data Models:** Draw out the models and any associations for your project in an entity relationship diagram (ERD).
* **Milestones:** Outline the milestones/sprints for your group.
* **User Research:** Include the research results from product tests in your product design.
* **Delegating Tasks:** What will each group member work on? Leverage everyone's strengths, and spend the majority of coding time pair programming.

### Completed Project Deliverables

* Link to Heroku hosted project, with all core technical requirements and three flexible technical requirements complete.
* Link to source code on GitHub.
* A `README.md` file with the following:
  * Description: Short paragraph (2-3 sentences) "elevator pitch" describing what your project does
  * Wireframes and user stories
  * User research conclusions from testing with at least 3 users
  * Link to Heroku hosted project
  * Technologies (languages, external libraries, APIs)
  * Wish List / Future Development
  * Contributors (with links to their GitHub profiles)

---

## Technical Requirements

###### What technologies will we be using?

### Core Technical Requirements

**Your app should have all of the following:**

* **Node:** Use Node and Express as the core for the back end.
* **Angular:** Use Angular as the framework for the front end.
* **SQL:** Use a SQL implementation like MySQL or PostgreSQL for your database in development and production.
* **Data Models** Include at least two data models with associations.
* **Data Validation:** Your application should validate incoming data before entering it into the database.
* **Error Handling:** Forms in your application should also validate data, handle incorrect inputs, and provide user feedback on the client side.
* **Testing:** Write at least two unit tests for every model.
* **Views:** Use **partials** to follow DRY (Don’t Repeat Yourself) development in your views.
* **Home & About Pages:** Create a landing page (homepage) that clearly explains your app's value proposition and guides the user through the "get started" funnel. Create an about page that includes photos and brief bios of your team members.
* **User Experience:** Ensure a pleasing and logical user experience. Use a framework like Bootstrap to enhance and ease your CSS styling.  Make sure user flows utilize user and competitive research.
* **Responsive Design:** Make sure your app looks great on a phone or tablet.
* **Heroku:** Deploy your app to Heroku. Ensure no app secrets are exposed. *Do not commit secret keys to GitHub!*
* **User Login** Make sure you have authentication *and* authorization.

### Flexible Technical Requirements

**Your app should have at least 3 out of the 6 following options:**

* **AJAX** Use AJAX to communicate with the server without reloading the page when appropriate.
* **External APIs** Integrate third-party data into your app.
* **Paperclip** Upload files with Paperclip.
* **User-Friendly URLs:** Make pretty URLs that don't expose database IDs.
* **Angular Animations:** Use Angular to make page animations.
* **ES6:** Use the newest production version of Javascript to DRY out and improve your code.

---

## Further Exploration

###### What if we want to do more?

If you want to push yourself and learn something new, optionally consider doing any of the following ideas. *Please talk to an instructor beforehand.*

* **Charting:** Visualize your data! Possibilities include D3, Morris.js, Highcharts, Chart.js, and Google Charts.
* **Job Scheduling:** Set up a job-scheduler like Sidekiq, Delayed Job, or Resque to queue actions that don't need to run immediately.
* **Emails:** Use ActionMailer to send emails to your users.
* **Text Messaging:** Use Twilio to send texts to your users (note: not free).
* **Payment:** Use Stripe to allow your users to purchase from or donate to your site.
* **Material Design:** Research the material design paradigm and apply it to ground your app's UI in the physical realm.
* **Accessibility:** Research web accessibility (e.g. for blind users), and apply accessibility principles to your app.
* **Sessions:** Use sessions to store data for site visitors (who aren't necessarily logged in).
* **Search:** Build a form that allows users to search your data, based on attributes. Consider looking into Elasticsearch to speed up queries.
* **Whatever else you can think of!**

---

## Deadlines

###### When is it due?

* **Thursday, January 5th** - Project pitches.  You must be prepared to talk about the problem you are planning on solving, the proposed value added to your user, what you can do better than your competition, complete with wireframes and findings from user research.

* **Thursday, January 12th** - Completed project deliverables due and presentations!

---

## Submission

###### How do we turn in the project?

* As you make code changes, **frequently commit and push to GitHub**.  Submit the assignment (GitHub link) on Schoology on presentation day.


---

## Project Groups

###### Who are my group members?

#### Group 1 - TBD

* TBD

#### Group 2 - TBD

* TBD

#### Group 3 - TBD

* TBD

---

## Presentation Guidelines

###### What should we cover during our presentation?

Each group will present their project on **Thursday, January 12nd** starting at **1:30 PM**. Please follow these guidelines:

* Your presentation should include the **motivation** for building this project and a **demo** of the core functionality.
* **Maximum 15 minutes.**
* **Minimum 5 slides.** Slides should include:
  * Wireframes
  * User stories
  * ERDs
  * Walk through the development of one feature from ideation to execution. At minimum, this should include wireframes, code samples, and the final result.
* **ALL group members must speak during the presentation.** Each group member should answer the following:
  * What parts of the project did you work on?
  * What was the most challenging aspect? Was there anything that was surprisingly easy to implement?
  * What did you learn?
