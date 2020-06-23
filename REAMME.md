# Intro to the web

## Learning objectives

### Goals for the week

Ask yourself the same two questions:

- Are you having fun?

- Are you a better developer than you were yesterday?

#### Primary goal

By the end of the week, the goal is to be able to answer "yes" to the week's primary question:

- **Can you build a web app?**

### Reminder of all this week's goals from the [Week Outlines](https://github.com/makersacademy/course/blob/master/week_outlines.md)

By the end of the week all developers can:

* Build a simple web app (this primary goal breaks down into the sub-goals below)
* Follow an effective debugging process for web applications
* Explain the basics of how the web works (e.g. request/response, HTTP, HTML, CSS)
* Explain the MVC pattern

### Concepts and skills for the week

#### Concepts

- The relationship between a client and a server.
- How HTTP is used to send information over the web.
- RESTful APIs.
- The request/response cycle.
- Web templating with HTML/CSS.

#### Skills

- Debugging programs that use multiple languages.
- Using a framework (Sinatra) in your code.
- Structuring the code for apps that have user interaction and visual output.
- Testing apps that have user interaction and visual output.
- Tracing data between the browser and server.

## Structure of the challenges

- Some exercises to get you familiar with Requests, Responses, and HTTP
- A project to get you familiar with Servers, `params`, `session`s
- Some exercises to get you familiar with Capybara
- An extended project to wrap it all together


## Progress so far


This week we are focusing on understanding web elements and how the web works.

So far we've built our own local servers using Sinatra and allowed for constant updates via Shotgun meaning that we don't need to restart the server everytime we make a change to our codebase.

We've built a simple website that allows for dynamic interactions and randomly generating names as well as a separate website that allows the user to input a name into the page, click "Submit" and be able to interact with a name.

We've now shifted some of the functionality of the form from the index.erb to the cat_form.erb. This allows us to follow SRP and means that the form is self contained.
We also tested the functions for the GET and POST functions that we can see happening both in the console log as well as the Chrome web dev tools.