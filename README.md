# 1. Who is your client?
Our client, Edwin Huang, owns and operates a number of charcoal chicken shops around Victoria, under the brand name “Red Rocks Charcoal Chicken”. He splits his time between working in the stores as a manager, and doing all the administrative/entrepreneurial work as the owner.

# 2. What is your client’s need (i.e. challenge) that you will be addressing in your project?
One of Edwin’s biggest challenges is keeping track of employee hours worked, calculating overtime and calculating how much he owes in wages to each employee. Currently, his employees record how many hours they’ve worked on a paper form, and he manually updates his excel spreadsheet at the end of the week. It’s time consuming work and his employees often make mistakes which means he has to manually follow up with those employees to clarify the situation.

# 3. Describe the client’s current setup and data.
Red Rocks Charcoal Chicken does not currently implement a digital solution to this problem. They are currently using an excel spreadsheet to manage employee data and employee expenses. The managers of each store must manually update the spreadsheet at the end of every week- This is time consuming and could better be handled through the use of an app and database solution.

# 4. Describe the project will you be conducting and how your App will address the client’s needs.
We will develop an online app that will enable Ed’s employees to easily enter in the amount of hours they’ve worked. The app will automatically calculate the standard and overtime hours based on the information, and display this information on a dashboard that Ed can view. Ed can add/remove employees from the system and review the submissions before approving them. The dashboard will also include an overview of past wages paid, which he filter by various fields (dates, locations, employee, etc).

This app will streamline the process of calculating wages, reduce the number of errors and remove the need to manually update an excel spreadsheet.

# 5. Identify and describe the software (including databases) to be used in your App.
NodeJS Backend - Custom Express Stuff (Mongoose, etc)
MongoDB Database
React on Frontend
Framework?? - create react app? 

# 6. Identify and describe the network setup you will use in your development.
.

# 7. Identify and describe the infrastructure (i.e. hardware) that your App will run on.

Web App - DigitalOcean? Production plans?

# 8. Describe the architecture of your App.

Front-side: 1 app 

# 9. Explain the different high-level components (abstractions) in your App.

Talk about Employee vs Employer sections
Talk about 5 main pages: Employee Dash, Employer Approvals, Employer Reports, Employer Business Settings, Employee Management

# 10. Detail any third party services that your App will use.

Mail: Nodemailer? Sendgrid/Mailgun? 

# 11. Identify the database to be used in your app and provide a justification for your choice.

MongoDB

# 12. Discuss the database relations to be implemented.

ERD 

# 13. Provide your database schema design.



# 14. Provide User stories for your App.

Tick! Woo!



# 15. Provide Wireframes for your App.

Half Tick! Design / Prettier Wireframes on the way



# 16. Describe the way Tasks are being allocated and tracked in your project.

## [Main Scrum Trello Board](https://trello.com/b/DFlgggpu)

Task tracking and breaking out tasks to individual features was really important to our team dynamic. Early on, we had very frank and open discussions about the fact that we had a diverse team, with varying levels of time outside of class and confidence in abilities. We decided to work hard to implement agile practices and break down tasks into achievable chunks, so as to best work together to achieve our goals.

To that end, from the outset we implemented a main Scrum-style Trello board, split into a number of sections:

<a href="assets/images/scrum.png" target="_blank"><img src="assets/images/scrum.png" width="500"></a>

Link To: [Main Scrum Trello Board](https://trello.com/b/DFlgggpu)

### Ideas / Stretch Goals
> All our ideas started here - straight from our very first planning session after our initial client brief. New ideas land here first, are discussed and formed if agreed to, where they move to “Tasks”.

### Tasks
> All our main work starts here, first. ‘Tasks’ are usually larger chunks of work, including documentation, planning, and research as well as the obvious “App Feature” tasks. If necessary (mostly during development), these Tasks will be broken down into smaller “Features”, where they can be worked on by individuals. An example might be “User System (Model, Login, Logout, Auth)”

### Features
> Mostly used in the Development stage, “Features” are generally front or back-end pieces of code, that come together to make one functional piece of the App. An example might be “Frontend: User Login Form”

### To-Do (Next Few Days)
> The title is fairly self-explanatory, this is just a staging area for us to further breakdown our workflow. From here, we’ll decide at standup meetings who is going to work on which card.

### In Progress
> Self-explanatory- This is where we’ll hold the cards we’re currently working on. No card gets here without assigning a team member to it.

### Blocked
> If something is holding us up from work, we put the card here, and comment as to what the blocker is. The intention here is for us to help one another overcome the blockage, or rethink the card scope or timing.

### Pending Review
> Somewhere to put cards if we need another team member to check on the work or review the code.

### Completed
> Completed cards go here! Yay! 

### Access / Resources
> A collection of links we can use to quickly get around.

The board is designed to be self-documenting, and make sense, so as not to be too confusing. We decided against using many, smaller boards, in favour of one large board, where we can follow a card from original idea through to completion.

# 17. Discuss how Agile methodology is being implemented in your App.

From the outset of this project, we decided to take a lot from the Agile methodology. Given that each of us has our own unique strengths, we have embraced the idea that we will be far more powerful as a team, and the Agile (Specifically, Scrum) practices offer a lot in the way of organization. 

<a href="assets/images/ideation.jpg" target="_blank"><img src="assets/images/ideation.jpg" width="500"></a>

We kicked it off with a big Ideation whiteboard session. This was great in laying out what we needed and wanted to achieve given the client’s needs. From this, we started up our Trello board “Ideas” column, and the flow progressed from there.

<a href="assets/images/ideation2.jpg" target="_blank"><img src="assets/images/ideation2.jpg" width="250"></a> <a href="assets/images/postit.jpg" target="_blank"><img src="assets/images/postit.jpg" width="250"></a>

(We also had fun. Winter got *really* into his post-it notes :D)

We also agreed to daily stand-ups, so as to get one another on the same page as far as what we’re all working on. We had some big conversations about our plans to break down tasks and work together. We all agreed that whilst it’s important to lean on our strengths, nobody should have to feel as if they are “Carrying” any aspect of the project - from design, through to code. To this end, regular stand-ups, and breaking things down into achievable chunks were very important to all of us. 

Adding in a “Blocked” step to the scrum board was another big part of this. We agreed that if something’s holding us up, we can park the card here and move on to something else, after notifying the team or finding someone to help. We plan to hold weekly reviews- Perhaps not full “retrospectives”, as we may not have time, but at the very least borrow from the “safe, blameless space” ethos while holding these reviews.  

As far as Timeline planning goes, we have begun to track our progress using Maxi’s previously made Timeline Tracker app! 

<a href="assets/images/timeline.png" target="_blank"><img src="assets/images/timeline.png" width="500"></a>

This was actually really useful! It was really impressive and empowering to see how we could actually use a tool that was previously made by one of our own, to further our project needs. Thanks, Maxi! 

# 18. Provide an overview and description of your Source control process.

For version and source control, we will be using Git, with a main repository stored on Github. At this early stage we’ve planned to use a “Protected” `master` branch for pushing to production, and a `develop` development branch for working between releases. 

We have taken a lot of inspiration from this model: https://nvie.com/posts/a-successful-git-branching-model/ 

Master (Protected): The `master` branch is ‘Protected’ against any `git push` commands, and only able to be merged via Pull Request on Github. The idea behind this is that `master` is only to be used for stable releases that have been tested and checked thoroughly.

For individual features, Our plan is to use separate `feature` branches cloned off of the `develop` branch. These branches will be merged into the `develop` branch, after changes are pulled and conflicts resolved. We intend to push these `feature` branches as well, to keep a record of our progress, though this isn’t really necessary for a project of this scale.





# 19. Provide an overview and description of your Testing process.

TBC - Unit Testing? Basic Integration Tests

# 20. Discuss and analyse requirements related to information system security.

Lol hax - JWT’s, Cookies, No Local Storage, Hash Passwords, Upload all passwords in plain text to rainbow table

# 21. Discuss methods you will use to protect information and data.

Lol hax - JWT’s, Cookies, No Local Storage, Hash Passwords, Upload all passwords in plain text to rainbow table

# 22. Research what your legal obligations are in relation to handling user data.

Somebody to do some cursory research?


