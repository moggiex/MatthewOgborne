# Matthew Ogborne

Howdy, a simple log of what activites, courses etc...  I have been working on.

## MERN Stack Front To Back: Full Stack React, Redux & Node.js
> "Build and deploy a social network with Node.js, Express, React, Redux & MongoDB."

[![Video Image](https://img-c.udemycdn.com/course/240x135/1646980_23f7_2.jpg)](
https://www.udemy.com/course/mern-stack-front-to-back/)



| Course Contents       | Course Details|
|:------------- |:-------------|
| <ul><li>Build a full stack social network app with React, Redux, Node, Express & MongoDB</li><li>Create an extensive backend API with Express</li><li>Use Stateless JWT authentication practices</li><li>Integrate React with an Express backend in an elegant way</li><li>React Hooks, Async/Await & modern practices</li><li>Use Redux for state management</li><li>Deploy to Heroku with a postbuild script</li></ul>| <ul><li>**Source:** Udemy ([Link](https://www.udemy.com/course/mern-stack-front-to-back/))</li><li>**Author:** Brad Traversy</li><li>**Length** 12 hours</li><li>**Paid or Free:** Paid</li><li>**Repo:** [GitHub](https://github.com/moggiex/devconnector_2.0)</li><li>**Start Date** 18th Feb 2021</li><li>**Finish Date** TBC</li></ul> |

<details>
  <summary><b><u>:wrench: Tools Used (click to expand)</u></b></summary>
  
  * NodeJs
  * React
  * Redux
  * VScode
  * Postman
  * npm packages (Nodejs backend)
    * express
    * mongoose
    * config
    * bcryptjs
    * jsonwebtoken
    * express-validator
    * gravatar
    * request
    * nodemon
    * concurrently
  * npm packages (frontend)
    * axios 
    * react-router-dom 
    * redux 
    * react-redux 
    * redux-thunk 
    * redux-devtools-extension 
    * moment 
    * react-moment
</details>

<details>
  <summary><b><u>:notebook: Course Notes (click to expand)</u></b></summary>

This course was an ideal statring point to refresh myself with NodeJs, express and to gain hands on expereince with React, Mongo & redux. 

**Side Note:**  I previously completed [Node.js API Masterclass With Express & MongoDB](https://www.udemy.com/course/nodejs-api-masterclass/) in 2020 and used it to create an API for my own software product to automatically pull in data from eBay trading & shopping API's. NodeJs completed the tasks in seconds compared to my previous approach using PHP because of its asyncronous nature.

In reference to the integration above, NodeJS asyncronious nature was a blessing and a curse. It was an amazing challange to be able to keep track of all the concurrent API calls being made, as sometimes there were over 100 pages of listing data to retreive. In the end (after much frustration!) I was able to manage this by keeping a multidimensional array up to date for each eBay account with which pages had completed, then removing the page number from the array (and keeping track of the running total), so that if any pages failed, they could be requested at the end (with a falure count too, so not to get trapped in a loop). Source code available (private repo).

**Right back to this course!**

Routing in NodeJs is really straightforwards with Express (laravell ~~is~~ 'can be' a mess, Yii2 is civilised) and the the routes & models were broken up into logical files & folders (The Model and Controller, the "View" part is where React comes in). 

I had forgotten how well MongoDb can be structured with the use of Schemas. I'm used to RD with MySQl, the "document" approach is different for sure, but you can easily link documents with a reference (userid).

Authorisation checks of the JWT were made in a simple middleware file, along with the use of [express-validator](https://www.npmjs.com/package/express-validator) to validate user submiited data before progressing and to return applicable messaging via json if checks were failed.

### What I liked about this course
* Code-along, lead by example format to create a working app at the end of it
* The NodeJs side felt comfrotable from previos expeience
* Straight into working with React (haven't worked with before at all!)

### And disliked
* Some of the API calls were left lacking. Specifciacally the lack of pagination to limit the amount of data being returned and also some of the API calls did not have the option to update, just add or delete. Added @todo notes for these in the source, may return later to add these when more knowledgeable
* The course was a little older, discovered a few minor issues while working through. For example the removal of Switch from react-router-dom and the use of Routes instead
* 


</details>

## Social Network Theme With Sass
> "Four part series to create the theme used in the DevConnector site created in the MERN course above"

<img src="https://i3.ytimg.com/vi/IFM9hbapeA0/hqdefault.jpg" width="240">

| Course Contents       | Course Details|
|:------------- |:-------------|
| <ul><li>Setup Sass</li><li>Sass variables, mixins and functions</li><li>Create the 11 page templates from scratch</li><li>Sass utility classes & Sass logic</li><li>CSS grid template areas, flex and mores</li><li>Make the templates responsive with media queries</li></ul>| <ul><li>**Source:** YouTube ([Link](https://www.youtube.com/watch?v=IFM9hbapeA0&list=PLillGF-Rfqba3xeEvDzIcUCxwMlGiewfV&ab_channel=TraversyMedia))</li><li>**Author:** Brad Traversy</li><li>**Length** 2.5 hours</li><li>**Paid or Free:** Free</li><li>**Repo:** [LINK NEEDED](https://github.com/moggiex/devconnector_2.0)</li><li>**Start Date** TBC</li><li>**Finish Date** TBC</li></ul> |


