*Bjorn: Before reading my comments in this outline plase read what I wrote in bjorn_outline.md under App Design*

# Project Outline


## Summary and Goals
A To Do List that helps developers build a web app from start to finish. They go through the list, select/fill in the steps they need to do as they build the app.

---
*Bjorn: I really liked the overall idea here, a tool to guide you through building a web app. I have found myself kind of stuck on projects before. Where I knew I had a lot to do, but unsure what specifically to do next. This is definitely something I could use in those cases.*

---

## App Design
A mobile-first single page app for this first version. Users can input string values for fields, basically they type in the backend language they'll use or text editor, etc for list fields. Multiple to do lists can be made for multiple projects.

To Do list fields are "locked" until user fills certain fields in a certain order.

---
*Bjorn: Here I hit the first snag. I think developing a web app is rarely a step-by-step process. You often have to go back and forth between stages. Like us now thinking we were done with the outline stage, but ending up going back to it.*

*And also changing one thing in one part of the project might necessitate change in other parts of the project. I think it is important to take that into account when developing this tool.*

---

## App Flow


### Idea
User types simple project idea. This unlocks the Outline field.

### Outline
Just a simple check, unlocks sketch/wireframe.

### Sketch/Wireframe
Another simple check, unlocks Design.

### Design
Another simple check, unlocks Languages.

### Languages
This section branches into multiple fields: HTML/CSS, Javascript, and Backend.

#### HTML/CSS
User can fill in notes on basic HTML/CSS. These notes can include site structure, responsive design methods, and other important notes.

#### Javascript
User fills in notes on how this will be done such as using Vanilla JS, JQuery, etc.


#### Backend
User types in backend language to use, can also fill in notes.

##### Database
Types in database to use with backend, and notes.

---
*Bjorn: The app flow items are a good representation of our particular project, but I don't think they are universal. If for example I want to work on a small project by myself, I may not need to write out the idea and make a wireframe. I chose therefore not to include these specific items in my outline.*

*But the basic idea is really good. That is breaking a large task (the whole project) into smaller  tasks( Idea,Outline,Design,Languages), and then breaking them into even smaller tasks where appropriate (Languages into HTML,CSS,Javascript).*

*This is the point where I had my aha moment. The essence of programming is taking a task and breaking it into smaller tasks. If we can represent this process visually I think we will have a really good tool for developing a web app (and probably other software projects). If we visualize it successfully I believe what you would end up with is a kind of map of the whole project. With this map you would easily be able to spot what you need to work on to complete the project. I think a good way to visualize this is with the lists-within-lists approach I described under App design in bjorn_outline.md*

---

### Frameworks
User fills in a framework, if applicable. Field can remain empty.

### CSS Preprocessors
Fill in if applicable, can also remain empty.

---

*Bjorn: Other/new ideas:*

*As I wrote above under "App design". "Changing one thing in one part of the project might necessitate change in other parts of the project." This means that we need to have a fairly easy way to either*

*1)Make changes in other parts of the project from anywhere ("Make changes" in practice means adding new tasks or sublists) or*

*2)Use some form of messaging within the project as describen in bjorn_outline.md under Future Feature.*

---
