# Knockout Style Guide
This is an opinionated style guide for KnockoutJS syntax, best practices, ease of use and understanding code, structuring large KO applications. They are designed for making the code testable, reusable and flexible for large scale development. 

## Contribution
I would invite the community to add their best practices and make learning Knockout a quick and easy job along with quality coding. You can also provide your feedback on the listed practices and we are always open to accept the best reasonable answer.

## Purpose
This style guide will be a list of guidelines on how to structure Knockout code and what things are needed to be considered while building a MVVM application. Inviting other users to share their knowledge. [@TheTanna](//twitter.com/TheTanna)

This guide is explicitly for syntax, conventions and structuring of the Knockout Application. These are based on my experience working with this framework and delivering trainings as wells as seminars. If you wish to learn some basics about Knockout, please refer to the documentation [KnockoutJS](//knockoutjs.com/)

##Open Community
You will never learn alone from your own business scenarios. Go to [StackOverflow - KnockoutJS](//stackoverflow.com/questions/tagged/knockout.js) where you'd come accross thousands of questions describing various scenarios of other people. If you cannot contribute, you can gain some knowledge from their questions. 

##Guide
All we need to know is where to use which feature and how it would be useful to us. Once we know this then we would be able to fit the leggo bricks of a giant structure very easily.

##Before you proceed
I'd like you to have a look at this beautifully crafted answer on StackOverflow about [MVC vs MVVM](//stackoverflow.com/questions/667781/what-is-the-difference-between-mvc-and-mvvm) which explains a minute difference about frameworks like AngularJS and KnockoutJS

It states that "in MVVM, controllers will typically contain all processing logic and decide what data to display in which views using which view models." If you're wondering where did "C"ontroller came from, this means your data mappers which process the raw JSON coming from server and shape it into logical/meaningful grouping of data. Controllers listen for, and publish, events. Controllers provide the logic that controls what data is seen and where. Controllers provide the command code to the ViewModel so that the ViewModel is actually reusable.

So basically, this is what diagramattically happens in a large Knockout Application:
![MVVM Knockout Application Flow](https://raw.githubusercontent.com/ankittanna/knockout-style-guide/master/Slide1.PNG)

The diagram is self explanatory. 

In the diagram, we have seen the following role players:
    1. Information holder – an object designed to know certain information and provide that information to other objects.
    2. Structurer – an object that maintains relationships between objects and information about those relationships.
    3. Service provider – an object that performs specific work and offers services to others on demand.
    4. Controller – an object designed to make decisions and control a complex task.
    5. Coordinator – an object that doesn’t make many decisions but, in a rote or mechanical way, delegates work to other objects.
    6. Interfacer – an object that transforms information or requests between distinct parts of a system.

## Table of Contents

  1. [Single Responsibility](#single-responsibility)

## Single Responsibility

## Single Responsibility

### Rule of 1