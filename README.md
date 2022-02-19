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
  <summary><b><u>Course Notes (click to expand)</u></b></summary>

This course was an ideal statring point to refresh myself with NodeJs, express and to gain hands on expereince with React, Mongo & redux. 

I previously completed [Node.js API Masterclass With Express & MongoDB](https://www.udemy.com/course/nodejs-api-masterclass/) in 2020 and used it to create an API for my own software product to automatically pull in data from eBay trading & shopping API's. NodeJs completed the tasks in seconds compared to my previous approach using PHP because of its asyncronous nature.

**Side Note:** In reference to the integration above, NodeJS asyncronious nature was a blessing and a curse. It was an amazing challange to be able to keep track of all the concurrent API calls being made, as sometimes there were over 100 pages of listing data to retreive. In the end (after much frustration!) I was able to manage this by keeping a multidimensional array up to date for each eBay account with which pages had completed, then removing the page number from the array (and keeping track of the running total), so that if any pages failed, they could be requested at the end (with a falure count too, so not to get trapped in a loop). Source code available (private repo).

Right back to this course!

Routing in NodeJs is really straightforwards with Express (laravell ~~is~~ 'can be' a mess, Yii2 is civilised) and the the routes & models were broken up into logical files & folders (The Model and Controller, the "View" part is where React comes in). 

I had forgotten how well MongoDb can be structured with the use of Schemas. I'm used to RD with MySQl, the "document" approach is different for sure, but you can easily link documents with a reference (userid).

Authorisation checks of the JWT were made in a simple middleware file, along with the use of [express-validator](https://www.npmjs.com/package/express-validator) to validate user submiited data before progressing and to return applicable messaging via json if checks were failed.


| What I liked | And disliked  |
|:------------- |:-------------|
| - Easy to follow |  Several of the API calls were not complete. For example only the ability to create or delete was covered, so I left notes to modify this to update/create and went back and changed the finished project|

</details>


