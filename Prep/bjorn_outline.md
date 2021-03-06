# Project Outline


## Summary and Goals
A laid back project management app. Has no estimated times or deadlines, it just shows what the next task is.

## App Design
A mobile-first single page app for this first version. Users can create and share projects. These projects are basically a set of lists-within lists of tasks that the users can create and modify as they please. The point of this is that an individual or group of people can easily determine what task needs to be done next to keep the project moving forward. By splitting larger tasks into smaller more manageable chunks will make a large project seem easier and less daunting, and provide motivation by finishing small tasks.

There are only two types of data the user can create: List and tasks.
Tasks can be completed by clicking on them, and lists can ONLY be completed by finishing all tasks (and sublists) within it.

---

**Saad**:  
*I like this. I'll create a workflow/flowchart to better demonstrate it*

---


## Example of use
A user creates a Project and gives it a name(for example "front end web-app"). The user opens the project, and creates a list for each major component in the project (for example "HTML","CSS","JavaScript"). He then fills the lists in with the tasks he knows needs to be done at this point for example("HTML" => ["Set up skeleton","header","footer"] and so on for the other lists). After having started on the project he realizes that creating a header ("HTML=>"header") took longer then he thought. He therefore choose to split the header into separate tasks that is to turn the "header"-task into a list. He now edits the "header"-list to contain "make button" and "make menu". These tasks can be further split up if the user so chooses. The point of this is to make tasks seem smaller and more manageable, and give yourself a clear view of what specifically needs to get done.

*I think that even just for personal use, this could be valuable tool to view clearly what needs to be done in your own project.*

--- 

**Saad**:  
*I see where you're going with this. Instead of having locked-in categories, give the user the option to change list items. One idea I have, if it's even possible for us to implement, is to create a* **Master User** *who's the only one who can modify the* **Main List** *although this will most likely require a backend and a database, so it might not be a 1.0 feature.*

**Bjorn**:  
*I think we can implement a master user, and maybe even varying access (like add collaborators on github). Allthough probably not in v.1.0. We probably want to focus on making the basic app first, but it is definitely somehing we'll implement eventually. Regarding backend and database. I think we already require a simple backend and we can "fake" a database with a JSON file. This isn't that much of a hassle though and will probably make implementing a database easier later on.*

**Saad**:  
*I don't know if you got the chance to look at my app flow chart yet, but where I'm going with this is kind of a cloud-based to do list. If we can make it cloud-based, I don't think we'll need to worry as much about creating master users for lists.*

---

## Future feature
There is one more feature though that I think is important, but it hasn't fully crystallized in my mind. That is a form of internal messaging in the project. Not directly between people but inside the project itself. My scenario for this idea is that the project is a collaboration between people with different expertise/area of responsibility. And say for example the front-end guy needs something from the back-end to work, in order for him to be able to continue. Instead of editing the lists and tasks in the "back-end"-list (Since he's the front-end guy he might not be familiar with what back-end needs to do). He sends a short message to the "back-end"-list (not the back-end guy, the list) of what needs to get done, also perhaps show where the message was sent from (e.g "front-end"->"javascript"->"AJAX").

*I'm unsure how to solve the future feature, but I think we need to have some form of internal messaging or something. It is important that the user can effectively contribute to a project without perfect knowledge of that project.*

---

**Saad**:  
*Perhaps the idea about the Master User can be put as a future feature.*

**Bjorn**:  
*I realize now that calling this topic "Future feature" was a bad choice of words to use. The feature I mentioned, or something like it, is something we need in v.1.0. I mention why in Saad_outline.md in a recent response to you. And yes Master User is definitely something we will need in future.*

**Saad**:  
*Whatever we call this section, Future feature or otherwise, isn't so important. We should definitely add ideas we have to it, or move ideas we currently can't do to this section. But I think one problem we'll both have is getting too caught up in what we want to do instead of what we can do. So definitely let's keep this here, but not make it as important.*

---
