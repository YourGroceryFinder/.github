# Your Grocery Finder

![](https://media4.giphy.com/media/v2QU1eGT5fnpV8Wjqo/giphy.gif?cid=ecf05e47khnf8r5rmifc1pkcx62weuzh20xwkxm15xq92id3&rid=giphy.gif&ct=g)

This semester we had to reach sertain learning outcomes. These are the following:
+ [1. Web application](#1-web-application)
+ [2. Software quality](#2-software-quality)
+ [3. Agile method](#3-agile-method)
+ [4. CI/CD](#4-ci-cd)
+ [5. Cultural differences and ethics](#5-cultural-differences-and-ethics)
+ [6. Requirements and design](#6-requirements-and-design)
+ [7. Business process](#7-business-process)
+ [8. Proffessional](#8-professional)

For every learning outcome there will be a clarification and how i reached that outcome.

# Learning outcomes S3
## 1. Web application

### Small explanation.
My project is called YourGroceryFinder. I want to create a website where you can easily find where your favorite brand groceries are sold. 
I got this idea when i really wanted my favorite energy drink but i couldnt find it in the stores close to my house.
When this happend I thoutgh I would really appreciate one place where I can find any product in all the stores, so that is what i tried to make this semester.

To challenge myself i went for all new programming languages. I used Java for my back-end and Vue 3 for my front-end. I have never worked with these before but during this project i am hoping to learn allot about them.

### How it Works
Your Grocery finder works by getting all of the items from different stores into a database and then showing it to the user.
For this i need a few different things:
+ A front-end where the user can search for products. See [YourGroceryFinder Front-end](https://github.com/YourGroceryFinder/YourGroceryFinder_Front-End)
+ A back-end that connects the front-end with the database. See [YourGroceryFinder Back-end](https://github.com/YourGroceryFinder/YourGroceryFinder_Back-End)
+ A Scraper to get all the products from the different websites. See [YourGroceryFinder Scraper](https://github.com/YourGroceryFinder/YourGroceryFinder_Scraper)
+ A database where all the products are stored.

## 2. Software quality

### Tests

### Sonar cloud
To keep a high quality of software i use sonarcloud. Sonarcloud uses state-of-the-art tchniques in static code analysis to find priblems and potential problems in the code that you have written. 
It also supports the reporting of test covrrage as part of analysis. It doesnt do it itself tho, it needs a third-party tool to be set up to produce the reports as part of your build process. This is why i decided not to use it. 

## 3. Agile method

### What is agile
Agile is a certain approach to project management and software development. By being iterative and flexible it features adaptability, collaboration and delivering value to customers in shorter timeframes. 
The agile approach focuses on having increments in your project called sprints. Each team decides how long a sprint can be. I have worked in projects where the sprints lasted one week and projects where they lasted up to three weeks. The goal is to create a result at the end of a sprint which can be reviewed, tested and improved/adjusted after receiving feedback.
Agile has a few key principles:

1. Customer collaboration over contract negotiation.
   In agile it is important to see your customers/end-users as part of the team. This way there will be more involvement and makes them and you understand better what their needs are.
   
2. Responding to change over following a plan.
   It is always smart to have someone of a plan set up like requirements and things like that. But with agile they aren’t set in stone. Agile recognizes that requirements can change during a project.
   
3. Working product over comprehensive documentation.
   Agile emphasizes delivering a working product or prototype over big documentation. While documentation is still important, it isn’t as much for the customer. They want to see a result and the sooner they have an image, the better and more detailed feedback they can give.
   
4. Individuals and interactions over processes and tools.
   Agile values the importance of effective communication and collaboration among team members. While processes and tools are essential, the emphasis is on empowering individuals to work together.

### Which agile methods mostly used?
There are many different agile methods. 8 of the most used agile methods are:
1.	Scrum
2.	Kanban
3.	Lean
4.	Extreme programming(XP)
5.	Feature-Driven Development(FDD)
6.	Dynamic Systems Development Method(DSDM)
7.	Crystal
8.	Adaptive Software Development

The ones that stand out to me the most are Scrum, XP and FDD. This is what I found about them:
- Scrum
  Scrum is one of the most popular and widely adopted agile frameworks. It involves dividing work into short iterations called sprints, usually lasting 1-4 weeks. Scrum teams have defined roles, including a product owner, Scrum Master, and development team. Daily stand-up meetings, sprint planning, sprint reviews, and retrospectives are key Scrum practices.
  
- XP
  Extreme Programming is a development approach that emphasizes close collaboration between developers and customers. It promotes practices such as frequent releases, continuous testing, pair programming, collective code ownership, and regular feedback from customers. It sounds like a more approachable way for beginning teams with new programmers.
  
- FDD
  Feature-Driven Development is a feature-centric approach. It involves creating a feature list, developing features incrementally, and emphasizing domain modeling and design. It sounds like a approach I would use if I worked alone for a long time. Unlike scrum it doesn’t have the meetings every morning to talk about what everybody is planning to do or things like that. Its more less focusing on user stories and more on single features. 

### My Choice
I choose to go with Scrum. Even though I did mention that FDD is more of a single person team approach, it feels that scrum is a better way of involving anybody that I need to involve. I also think because scrum is one of the most used methods of agile it is very useful to learn it. What I like most about scrum is the sprint reviews, planning and the retrospectives. What is expected of me, what can I achieve and how did it go last time.

## 4. CI/CD

#Redirect to documentation

### CI
For the CI tool im using Github Actions. I chose GitHub Actions because GitHub hosts it for me and it had easy configurations with the YAML file. Also is it very useful to have a wide range of tool to my disposure such as docker.

#### CI Pileline
When I think of a Git or CI pipeline I think of something like what is demonstrated in this picture.

![image](https://i.imgur.com/QmUpWHH.png)

You have the master of the main branch, this is your version control and your main application branch. 
From this branch you create a dev branch. This will be the branch where all development will be added together and checked if they work together.

If a new feature need to be added, a feature branch will be made from the dev branch, the feature will be made and then when that feature is finished you can merge it back into the dev and delete the feature branch. When you have multiple features added to your branch and a stable version of your application you can merge your dev branch into master to release a new version of your application.


### CD
A detailed explanation on how i performed my CD can be found [here](https://github.com/YourGroceryFinder/Documents/blob/main/DockerResearch.md).

## 5. Cultural differences and ethics

In our group project we went over a couple points that include the [ACM Code of Ethics](https://www.acm.org/code-of-ethics). I found it very hard to think about these points because our group never had any difficulty with it. We tried to give more details on the points that did aply to our group and you can find that information over here in our [Cultural differences and ethics file](https://github.com/wocevv/Documentation/blob/main/Ethics.md)

## 6. Requirements and design
>Clarification:
>
>Multiple types of test techniques: You apply user acceptance testing and stakeholder feedback to validate the quality of the requirements. You evaluate the quality of >the design (e.g., by testing or prototyping) taking into account the formulated quality properties like security and performance.

For my personal project i made a rough design if what i wanted my application to look like, you can find that [here](https://github.com/YourGroceryFinder/YourGroceryFinder_Front-End#design). I made it with Visio. For our group project we made a low and high -res desifn which can be found [here](https://github.com/wocevv/Documentation/blob/main/Design.md). This one is made with figma. I think for Creating a valid prototype figma is a better option for understand how the application looks and acts.

To better understand how userfriendly our application is and to imporve any difficulties we did some usability tests. You can find more information on those [here](https://github.com/wocevv/Documentation/blob/main/usability-test.md).

## 7. Business process

Our group had allot of communication with our stakeholders. We wnated to involve them in every descision we made so that we could deliver the producted they wanted most. We send them our ideas and sketches for the designs, at the end of every sprint we send them the targets for the next sprints and things like that. 

## 8. Proffessional

### Individual
In the individual project I made a mistake. I didnt have enough contact with my stakeholder which made it hard for him to grasp where my progress was at. However the times that i did speak with the stakeholder I made sure to always keep the feedback in mind for the next sprint and reflect on what i did the srpint before.

### Group
The communication with the stakeholder in the group project went allot better. Every sprint we contacted the stakeholders for every question we had that could only be awnsered by them. After every presentation we gave we made sure to ask for extra feedback to make sure we worked on the parts that they wanted us to focus on and which they thought were most important. 
