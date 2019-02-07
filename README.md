# Five Stars Mowing
### Michelle Bryant, James Hicks, Beth Callanan, Thanh Dao, Jaouad Sourour

 ##### Deployed live on heroku at <a href="https://fierce-earth-84978.herokuapp.com" target="_blank">https://fierce-earth-84978.herokuapp.com => CTRL+click on the link to open in a new window</a>
##### visit our repo at https://github.com/thanhthedev/react-project-server

## Description of Project
#### This is a web-app for Troys five star mowing business where viewers can see: 
   * Services
   * Feedback
   * Location 
   * Quote.
  
### Problem definition / purpose
Our client was relying soley on facebook and word of mouth to attract potential clients for his lawn mowing business. The purpose of the web application is to display the services Troy has to offer, his location and travel limitations as well as a form for potentials to fill out to request a free quote.

### Functionality / features
We have built Five-Star Mowing’s business website with the following pages and content: 
  * Home → carousel of images of completed jobs, brief list of services, map showing business base location
  * About → an image of the business owner and short description of the business
  * Services → a full list of the services provided by the business
  * Feedback → clients can leave feedback about the completed jobs
  * Quote → contains an image of the process of quoting and booking, and has a form that a visitor can fill out and submit to request a job quote, which sends an email to the business owner with the details required

### Screenshots

#### Application Screenshots:
#### Mock up of homepage
![home-page-mock](https://user-images.githubusercontent.com/38389703/52257675-6d156600-2967-11e9-8e36-d51ad5304b7e.png)

#### Landing page 
![landing-page](https://user-images.githubusercontent.com/38389703/52313738-620c1580-29fb-11e9-9ae3-30c6c80134ec.png)

#### Services on homepage
![sevices-home-page](https://user-images.githubusercontent.com/38389703/52313752-6fc19b00-29fb-11e9-8e5b-e052a3547133.png)

#### Home page map
![map footer-homepage](https://user-images.githubusercontent.com/38389703/52313760-77813f80-29fb-11e9-9078-47642be462ac.png)

#### feedback page
![feedback-page](https://user-images.githubusercontent.com/38389703/52313767-7d772080-29fb-11e9-82fa-cab8d1b69060.png)

#### Quote form
![quote-form](https://user-images.githubusercontent.com/38389703/52313841-d5ae2280-29fb-11e9-8c76-a141704fd56a.png)

#### Form interaction
![site-form](https://user-images.githubusercontent.com/38389703/52313854-dfd02100-29fb-11e9-9c7f-b5376b0f98c8.png)

#### About page
![about-page](https://user-images.githubusercontent.com/38389703/52314004-697fee80-29fc-11e9-9979-0710b4b53c32.png)

#### Services page
![services-page](https://user-images.githubusercontent.com/38389703/52313847-da72d680-29fb-11e9-8981-2f46882be35c.png)

#### Testing Screenshots:
1 initial component rendering
![testing screenshot 1 initial component rendering](https://user-images.githubusercontent.com/42342586/52385260-7704a980-2acc-11e9-9f10-1c8f74e28a71.png)
2 GET services to form field
![testing screenshot 2 get services to form](https://user-images.githubusercontent.com/42342586/52385261-779d4000-2acc-11e9-8219-5856c7a74935.png)
3 POST form data
![testing screenshot 3 post form data](https://user-images.githubusercontent.com/42342586/52385262-779d4000-2acc-11e9-9f15-8afb36684f4a.png)
4 Correct data fow through mailer middleware
![testing screenshot 4 correct data flow through mailer middleware](https://user-images.githubusercontent.com/42342586/52385263-779d4000-2acc-11e9-85b0-666278e719d2.png)
5 Responsiveness on Heroku deployment
![testing screenshot 5 responsiveness on heroku](https://user-images.githubusercontent.com/42342586/52385264-7835d680-2acc-11e9-9228-f8f47100145b.png)

#### Team Communication Screenshots:
![team communication screenshot 1](https://user-images.githubusercontent.com/42342586/52385244-6eac6e80-2acc-11e9-877e-d68963fc5fca.png)
![team communication screenshot 2](https://user-images.githubusercontent.com/42342586/52385246-6eac6e80-2acc-11e9-9c34-3da02b5cb971.png)
![team communication screenshot 3](https://user-images.githubusercontent.com/42342586/52385247-6f450500-2acc-11e9-940f-860f3800247f.png)
![team communication screenshot 4](https://user-images.githubusercontent.com/42342586/52385248-6f450500-2acc-11e9-8519-62a881f1e291.png)
![team communication screenshot 5](https://user-images.githubusercontent.com/42342586/52385249-6f450500-2acc-11e9-97af-c35f9cbbd36b.png)

### Tech stack (e.g. html, css, deployment platform, etc)

  * MongoDB+Mlab → The database containing a list of services which is pulled into the quote form page, and the quote forms that have been filled out and submitted.
  * Node+Express → Node.js is the runtime environment used during development, and Express.js is the application framework built on top of Node to enable the functionality for creating the server-side of our application.
  * React → React.js is a Javascript library that was used to build the front-end of our application, using its component system as the tool for disaplying information effectively and efficiently.
  * HTML+JSX → HTML-like syntax was used in JSX format for creating the core structure of our components built with React.
  * CSS+Bootstrap → CSS and Bootsrap were the tools used to style our components, pages and app as a whole.
  * Cloudinary → Cloudinary is a could-based content storing and serving tool, which we used to securely serve our images to the application.
  * Heroku → The deployment platform for our app, our project files were uploaded to the Heroku server so it can be accessed on the web.

### Instructions on how to setup, configure, deploy and use your App.

####Developer perspective;
  * Clone the git repo from https://github.com/thanhthedev/react-project-server
  * Open the project directory
  * Open a terminal/ console window
  * In the console; npm install
  * Once that has completed; cd client
  * npm install
  * cd ..
  * Open the project in a source code editor like Vscode
  * Use console command 'npm run dev' to run servers concurrently
  * Ready to Go!
  * For developing your own version, do the above plus the following;
  * Open config/keys_dev.js
  * Replace the database URI with your own, for example a link to a database on Mlab.com

####End user;
  * visit https://fierce-earth-84978.herokuapp.com/
  * from there, you can navigate via the links at the top of the page to; Home, About, Services, Feedback, Quote
  * On the Quote page, fill out the form with your details then click submit to send a request to Troy to inspect your property before making a booking for a job.

## Design 
### Design process

In the implementation and design of the project, tasks were allocated to specific members of the team. These tasks ranged from research, design, development or testing of the code for the site. Tasks were assigned through standup meetings that were conducted every morning, and were monitored primarily through verbal and slack communication. Trello was also utilised to assess the scale of the required tasks to complete.

### Specification Assessment
Client interviews and discussion
Assessed client viability
Confirmed client

### Research
-  Trello board  populated with specifications and criteria requirements to structure the design process.
Researched libraries and component design to assess what would be the best approach to solving client specifications.
Nodemailer chosen as email server
Redux-forms chosen as framework to create the form quote due to its high versatility and ease of use.
- Client Facebook image scraping

### Database Design and Development
Database models, quote and services constructed.
Dataflow diagram and quote process implemented.
Routes coded for implementation of the pages.


### Visual Design and Development
Visual design of pages - home, services, about, form.
Styling elements selected (i.e colour code and font)
Design libraries chosen


### Form Design and Development
- Components for form input constructed
- Experimented with component design utilising Redux
- Forms and React Widgets.
- Form required different input values - text input, select from a drop down menu, multi select options from the services pulled from the database, time picker and date picker.
- Widget utilised for date picker , because of difficulty in coding with localisers.
- Time picker was hardcoded because of the difficulty with localisers.
- Connected form submission to database using Axios

### Email Design and Development
- Implemented Nodemailer as the email process.
- Connected form submission to Nodemailer


### Testing
Manual Testing  was conducted on the site continually throughout the build process
Automated testing was conducted at the completion of the site to assess for any missed issues.

### User stories

#### As anonymous I can: 

1. View a homepage with before and after shots of lawns 
2. See a map of where mower man is placed with surrounding areas
3. Navigate site using nav-bar links including:
  * Home
  * About
  * Feedback
  * Quote
4. View  his contact details 

#### As anonymous when Quote is clicked I can:

1. Fill out details that will include:
  * Address and Suburb
  * Property type
  * Email
  * Name
  * Date of potential booking
  * Time of potential booking
  * Pick the services wanted from a dropdown list
  * Phone number
  * Personalise with a message


###  Workflow diagram of the user journey/s.
![user-flow-diagram](https://user-images.githubusercontent.com/38389703/52314238-908af000-29fd-11e9-9b35-61daf7332329.png)

### Wireframes

![home-page-wireframe](https://user-images.githubusercontent.com/42559562/52311383-77307680-29f2-11e9-95f2-ce4da939f55a.png)

![about-page](https://user-images.githubusercontent.com/42559562/52311391-7c8dc100-29f2-11e9-8002-c47c6e29bcce.png)

![services](https://user-images.githubusercontent.com/42559562/52311396-83b4cf00-29f2-11e9-926f-d4d373cdac64.png)

![form-wireframe](https://user-images.githubusercontent.com/42559562/52311399-87e0ec80-29f2-11e9-95c5-491595847777.png)

![homepage-smallmobile](https://user-images.githubusercontent.com/42559562/52311405-8c0d0a00-29f2-11e9-88ee-2f84cbf37fa5.png)

### Database Entity Relationship Diagrams

![entity relationship diagram - team 4](https://user-images.githubusercontent.com/42559562/52311127-ab576780-29f1-11e9-974c-03e246921f82.png)


### Data Flow Diagram

![data flow diagram](https://user-images.githubusercontent.com/42559562/52323525-140e0680-2a29-11e9-8f15-42f7a8471f0a.jpg)

### OO design documentation

The design of this project in React required numerous components to be used across the site. The layout of the website, including the navbar, footer and home page and the quote form are built utilising components.

Navbar, footer and home page are individual components which define the layout of each page with classes. 


Quote Form Components

The quote form utilises both a component, which defines the layout of the form, as well as a form container which determines the actions required for the form to complete.
This was the design layout required for utilising the Redux Form library. 

The components designed for each field input of the form are:

Text

A simple text input field for the user to enter information. Simple validation of the text input is also implemented.
The text component utilises input as a props, which change depending on the value of what the user inputs.

Select

‘Select’, allows the user to choose from a list of predefined values in filling out the quote form. 
The select component is utilised in the for the ‘property type’ and the ‘inspection time’.

Select utilises option as a prop, as well as a key and index for the  options rendering.The data input for the predefined select values are hardcoded as an array in the form.component


Multi select
The ‘multi select’ component, utilises rendering capabilities from the React widgets library. This component allows the user to select or deselect possible service options. 

‘Multi select’ also requires logic from the React widgets library , which will pull in values for input, data, value field and textfield. 

Unlike the ‘Select’ component which utilises an array for the data, ‘Multi select’ requires Axios GET to retrieve the services data which are stored in the database. 


Date picker

‘Date picker’ is also a React widget. It also required a localiser library, ‘Moment’ to help define the states within the component. ‘Date picker’ utilises state to define the date as well as the date changes. 


## Project Management & Planning process including,

![manual-tests](https://user-images.githubusercontent.com/38389703/52385015-a36bf600-2acb-11e9-97b3-90bfbe6cc7f7.png)

### Project plan & timeline
![project-timeline](https://user-images.githubusercontent.com/38389703/52384442-33f50700-2ac9-11e9-9a6f-8eca688664f4.jpg)


### Client communications
![client-comunications](https://user-images.githubusercontent.com/38389703/52384323-c34dea80-2ac8-11e9-8de4-a5b9c18fdf27.jpg)

###  !You will find in the Docs folder a audio file pertaining the main communication we had with our client as he is located in Caboolture and was not available to meet in person. 

#### potential client record
In the same docs folder there is a file with the email correspondence from our first potential client KatieB. 

### Screenshots of Trello board(s)

![trello screenshot 1](https://user-images.githubusercontent.com/42342586/52383906-0909b380-2ac7-11e9-8d84-1d5a4b93948d.png)
![trello screenshot 2](https://user-images.githubusercontent.com/42342586/52383908-0909b380-2ac7-11e9-9abb-347f04cba210.png)
![trello screenshot 3](https://user-images.githubusercontent.com/42342586/52383909-09a24a00-2ac7-11e9-950a-c675761fae42.png)
![trello screenshot 4](https://user-images.githubusercontent.com/42342586/52383910-09a24a00-2ac7-11e9-997f-745388fd6f5e.png)
![trello screenshot 5](https://user-images.githubusercontent.com/42342586/52383911-0a3ae080-2ac7-11e9-8323-4a8a7f8d4d62.png)
![trello screenshot 6](https://user-images.githubusercontent.com/42342586/52383912-0a3ae080-2ac7-11e9-875a-ed416e21d045.png)
![trello screenshot 7](https://user-images.githubusercontent.com/42342586/52383914-0ad37700-2ac7-11e9-9fc7-4491a6e249fd.png)
![trello screenshot 8](https://user-images.githubusercontent.com/42342586/52383915-0ad37700-2ac7-11e9-933a-21f63f053071.png)
![trello screenshot 9](https://user-images.githubusercontent.com/42342586/52383916-0ad37700-2ac7-11e9-8317-8e7ea3a5e1e1.png)
![trello screenshot 10](https://user-images.githubusercontent.com/42342586/52383917-0b6c0d80-2ac7-11e9-9621-2c076a09a90f.png)
![trello screenshot 11](https://user-images.githubusercontent.com/42342586/52383918-0b6c0d80-2ac7-11e9-94b0-c34887e9e78a.png)
![trello screenshot 12](https://user-images.githubusercontent.com/42342586/52383920-0c04a400-2ac7-11e9-9efa-37940de0e7fc.png)
![trello screenshot 13](https://user-images.githubusercontent.com/42342586/52383921-0c04a400-2ac7-11e9-9a7e-0537c3c1d87f.png)
![trello screenshot 14](https://user-images.githubusercontent.com/42342586/52383922-0c9d3a80-2ac7-11e9-9860-81dfc5626fcc.png)
![trello screenshot 15](https://user-images.githubusercontent.com/42342586/52383923-0c9d3a80-2ac7-11e9-8a2f-dedf36795686.png)
![trello screenshot 16](https://user-images.githubusercontent.com/42342586/52383924-0c9d3a80-2ac7-11e9-8367-b922446c075a.png)
![trello screenshot 17](https://user-images.githubusercontent.com/42342586/52383925-0d35d100-2ac7-11e9-8372-39170815e815.png)

## Short Answer questions 
### 1. What are the most important aspects of quality software?

Functionality, structural quality and the process of development for apps greatly contribute to creating quality software.
Functionality is defined as how easy the app is to use. In consumer applications, if the app has a well defined user workflow, complete with a good aesthetic, the consumer will be more inclined to use said app.  If an app has a convoluted workflow, regardless of its aesthetics, it will prevent the user from utilising the apps full functionality.  

A way to ensure the functionality of an application can be through writing automate tests for the app. This will assist in identifying any issues that can occur when a user is operating the app. 


By making sure the code is readable and understandable for others can make the application flow from legacy code to new written code with little confusion.   
Having a strong structure for the code also assists in developing security for the app. 

Developing code that guards against accidental security vulnerabilities such as logic flaws or defects can be helped by identifying previous flaws and taking proactive steps that can reduce the vulnerabilities.  

Lastly, the quality of the development process will affect the longevity of the app. By making the app development process repeatable will ensure that there can be further iterations of the product or future developments on it. A repeatable development process includes the project management of the app, such as meeting deadlines and budgets. 

### 2. What libraries are being used in the app and why?

  * Bootstrap 4 – is a CSS framework used for styling responsive, mobile-first websites. This made it easier to style all our pages in a global format.
  * React.js – is a Javascript library use for building efficient and flexible user interfaces. We used it for its component feature, allowing us to easily structure our code and have it built to maximise extensibility.
  * Nodemailer – is a module for Node.js for ‘easy as cake’ email sending. We used it to forward an email to the business owner from a form on the website which can be filled out by any visitor.
  * Redux – is a state container for javascript applications which helps you manage the stored and displayed data and how you respond to user actions.
  * Axios - is a Javascript library used to make HTTP requests from node.js or XMLHttpRequests from the browser that also supports the ES6 Promise API
  * Concurrently – is a node.js package used to run multiple commands conurrently. It allows for easier testing during development, as there is only one terminal needed to run the servers.
  * Cors - is a node.js package for providing a middleware that can be used to enable cross-origin resource sharing with various options
  * Express - is a node.js framework that facilitates the rapid development of web and mobile applications. It allows the setup of middlewares to respond to http requests, defines a routing table to perform actions and allows dynamic rendering of html pages based on arguments and templates.
  * Express-router – is a library for organising the back-end routes of an express application. It helps us set up and use routes quickly and effectively.
  * React-router-dom – is an extended version of react-router library, which enables dynamic route matching to keep your UI in sync with your URL
  * React-reveal - is an animation framework for React. It's MIT licensed, has a tiny footprint and written specifically for React in ES6. It is used to create various reveal-on-scroll animations in your application.
  * React-slick – is an image carousel component used to display a gallery of images in an animated slider.
  * Cloudinary – is a cloud-based image and video management platform used to store and serve content to web applications.
  * Moment – is a date library for parsing, validating, manipulating and formatting dates.
  * React-widgets – is a set of extensible and accessible form inputs built for react
  * Jest - JavaScript Testing Framework with a focus on simplicity 
  * React-test-renderer - makes it easy to grab a snapshot of the "DOM tree" rendered by a React DOM or React Native component without using a browser or jsdom
### 3. A team is about to engage in a project, developing a website for a small business. What knowledge and skills would they need in order to develop the project?


Skills: 
### Communication 
   * Gain a mutual understanding and agreement by listening to what the client wants and also making the client aware of your limits such as time and/or budget.
   * Be assertive to prevent client from deferring from the agreed upon plan.
### Time management 
  * A clear and precise project plan that is revisited and readjusted where needed throughout the course of the project will keep developers on the task at hand. 
  * Have a plan in place and work around the tasks needed to finish instead of just basing it on time to complete
### Attitude 
  * Go into the task with a clear head and a positive attitude. Be ready to collaborate with team members. Share your weaknesses and strengths if you have to and always ask for help.
### Problem solving
  * In any project there will be a certain amount of problem solving needed to complete it, so it’s important to know good problem-solving practices. Analyse the problem in parts instead of a whole to prevent getting overwhelmed, be open to suggestions from others (not everyone thinks like you).
  
Knowledge:
### Programming language
  * It goes without saying you will need programming knowledge to complete a project like this, however you can complete it with even a basic understanding of the language and framework, google the rest.


### 4. Within your own project what knowledge or skills were required to complete your project, and overcome challenges?

In our project we each implemented adequate time-management skills, although our communication sometimes wasn’t the greatest. All were confident enough to start on a feature and work separately but when needed, worked equally well as pairs or more trying to fix a bug.  

### 5.Evaluate how effective your knowledge and skills were this project, using examples, and suggest changes or improvements for future projects of a similar nature?

### Jaouad:
  Based on My knowledge and experience in design area, helped the team to build an humble template for the project and i took care of the landing page, using some functuinality like react frameworks, like react-slick, react-reveal, react-scroll....ect, and i managed to create and deploy one repo including the server and client instead two repos. At the end of the day, i see that i have graspped the fact that i need to be more orginised and learn how to cope with the time management when its running from me. 
  
  
  

### James:
I understand the individual libraries and frameworks but have difficulty with the configuration between them. Also, when I see something built with different syntax as to how we learnt it in class I feel very lost. For example, I was referencing the slides and lectures for react and redux to work out how to get information from the store state, but the configuration was completely different in the store and reducer files so I had no idea how it was working. I had a similar issue with an onSubmit function and handleSubmit function, where I could see where they were initially defined, so could not distinguish how to manipulate their functionality. The projects themselves I think are good. I think more class time could be spent on understanding HTTP requests and how to deconstruct pre-defined functions and classes in APIs/ middleware/ imported libraries.

### Michelle:

In this project, I was given the opportunity to code and create the quote form that would be submitted to the database and the mailer. 
In the research and planning part of the project, my ability to research and assess what would be the best option forward helped to scope the project. For example in using Nodemailer for the email submission of the form and not emailing the form as a pdf. 

### Thanh:
My knowledge and skills in node.js have been effective and have improved, however my react skills need more improvement. I understand nodemailer, routes, models, mlabs and heroku better. Testing is hard.

### Beth
Throughout this project I’ve felt while my knowledge, skills and confidence may be lacking working in a group that is quick to help out made me work harder at a problem. It’s hard to translate what we’ve learned in class to a real-world application but searching through the resources that we have, and the problem-solving skills we have accumulated throughout the course make it less overwhelming. I worked on validation and design aspects which I loved even when I couldn’t solve the problem my group made it a safe place to be stuck.   
