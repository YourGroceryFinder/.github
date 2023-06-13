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

>Clarification:
>
>User friendly: You apply best practices when creating user interfaces and basic user experience testing and development techniques.
>
>Full-stack: You design and build a full stack application using a commonly accepted front end Javascript framework and back end application implementing relevant >communication protocols, persistence of data by usage of ORM and addressing asynchronous communication issues.

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
>Clarification:
>
>Tooling and methodology: Carry out, monitor and report on unit integration, regression and system tests, with attention for security and performance aspects, as well >as applying static code analysis and code reviews. It shows you the bugs you have, codesnells, security vulnerabilties, security hotspots and duplications. 

### Tests

### Sonar cloud
To keep a high quality of software i use sonarcloud. Sonarcloud uses state-of-the-art tchniques in static code analysis to find priblems and potential problems in the code that you have written. 
It also supports the reporting of test covrrage as part of analysis. It doesnt do it itself tho, it needs a third-party tool to be set up to produce the reports as part of your build process. This is why i decided not to use it. 

## 3. Agile method
>Clarification:
>
>Choose: You are aware of the most popular agile methods and their underlying agile principles. Your choice of a method is motivated and based on well-defined >selection criteria and context analyses.

### Jira

## 4. CI/CD
>Clarification:
>
>Design and implement: You design a release process and implement a continuous integration and deployment solution (using e.g. Gitlab CI and Docker).

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
>Clarifications:
>
>Recognize: Recognition is based on theoretically substantiated awareness of cultural differences and ethical aspects in software engineering.
>
>Take into account: Adapt your communication, working, and behavior styles to reflect project stakeholders from different cultures;
>
>Address one of the standard Programming Ethical Guidelines (e.g., ACM Code of Ethics and Professional Conduct) in your work.  

#Group project wait

## 6. Requirements and design
>Clarification:
>
>Multiple types of test techniques: You apply user acceptance testing and stakeholder feedback to validate the quality of the requirements. You evaluate the quality of >the design (e.g., by testing or prototyping) taking into account the formulated quality properties like security and performance.

### --

## 7. Business process
>Clarification:
>
>Simple: Involving stakeholders, predominantly sequential processes with one or two alternative paths.
>
>Related: Business processes during which the software that you are developing will be used (business processes that the software must support by fully or partially >automating them). 
>
>or
>
>Business processes needed for the success of your software development project (e.g., product release, market release, financial assurance).

### Show communication with group and stake holders

## 8. Proffessional
>
>Clarification:
>
>Professional manner: 
>
>You develop software as a team effort according to a prescribed software methodology and following team agreements. You are able to track your work progress and >communicate your progress with the team.
>
>You actively ask and apply feedback from stakeholders and advise them on the most optimal technical and design (architectural) solutions.
>You choose and substantiate solutions for a given problem.

### Individual
In the individual project I made a mistake. I didnt have enough contact with my stakeholder which made it hard for him to grasp where my progress was at. However the times that i did speak with the stakeholder I made sure to always keep the feedback in mind for the next sprint and reflect on what i did the srpint before.

### Group
The communication with the stakeholder in the group project went allot better. Every sprint we contacted the stakeholders for every question we had that could only be awnsered by them. After every presentation we gave we made sure to ask for extra feedback to make sure we worked on the parts that they wanted us to focus on and which they thought were most important. 
