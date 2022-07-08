<h1># cautious-octo-chainsaw</h1>
<h2>UoA PGCert Alum code club collab CMS/blog</h2>

<p>In order to work on a repository, it's strongly encouraged to use the workflow GitHub recommends:</p>
<pre><ol>
<li>Create a branch</li><li>Make changes</li><li>Create a pull request</li><li>Address review comments</li><li>Merge your pull request</li><li>Delete your branch</li>
</ol>
<a href="https://docs.github.com/en/get-started/quickstart/github-flow">Details on recommended workflow</a></pre>


<h2>Intro</h2>
<p>This project is to intended to practice skills from 719 and create a content management/blog web-app that the team can use as a collaboration/knowledge base.</p>

<h2 style="text-decoration: underline">Steps/Status and contributors:</h2>

<p> Simple overview of a plan to keep us on track to getting to end product </p>

| Step | Description | Status | Contributors |
| ---- | ----------- | ------ | ------------ |
| Agree scope | Decide on the broad scope for the project | Done 1/7/22 | Rich/Leanne/Max |
| Set requirements | Open to all to propose requirements within the broad scope | OPEN | TBC | 
| Produce a wireframe | Scratch-design, including look and feel and design-view of functionality to meet requirements   | Not started | TBC | 
| Divide-up dev work | break-up code required and get cracking!  | Not started | TBC |
| Test and debug | confirm functional requirements met | Not started | TBC |
| Release v1.0.0 | Beta Release | Not started | TBC |
| Beta Testing   | use app in anger/bug fix and patch, plan any other major releases | TBC |   


<h2 style="text-decoration: underline">Current Stack Proposal</h2>

<p> The technology stack suggested: </p>

| Component    | Software                 | 
| ------------ | ------------------------ |
| Database     | SQL or NOSQL (Cloud)     | 
| Back-end     | Node/Express             | 
| View Engine  | TBA                      | 
| Front-End/UI | TBA                      |           


<h2 style="text-decoration: underline">Requirements:</h2>

<p>Current set of requirements for verison 1.0.0.  Only suggestions at this stage</p>

| ID  | Requirement | Purpose/Description  | 
| --- | ----------- | -------------------- | 
| 1   | Wireframe agreed | Design and functional guidelines for the UI in sufficent detail help us code up all requirements consistently enough | 
| 2   | Layout-view in HTML/view engine format | a page template including functional navigation |  
| 3   | Welcome Page | Simple home screen with option to sign-in or create a new account.  Routing to bypass to to a different landing page if visitor already has an account and is using a regonised device |
| 4   | Users can create an account | Users can create an account by chosing a username, adding an email address and selected a password. Usernames must be unique and passwords must conform to following: <ul><li>min 8 characters length</li><li>must contain at least 1 uppercase char</li><li>must contain at least 1 special char</li><li>must be entered twice at time of creation by user</li></ul> |
| 5   | Passwords are stored with appropriate security| User password's are hashed and salted when saved and stored only as the hash within the db | To Do |
| 6   | Users are required to sign-in and are authenciated when accessing resources | Only users with accounts can access resources beyond using creating account/login features. Each and every request for a resource to the server is authenciated. | To-Do |
| 7   | Landing Page | Home page for authenticated users,  preview profile (messages/comments/posts) and ???  |
| 8   | Rich Text Editor |  NOT tinyMCE but simliar for all required CRUD operations |
| 8   | Advanced Content Navigiation |  Tree or simliar GUI enabled navigation to browse all content.  Consider async content loading as a stream for useing scroll function? |  
| 9   | Create posts |  A consistent form view enabling users to post new content
| 10  | Read posts |  A area or page dedicated to reading and interacting with existing posts<ul><li>up/down vote?</li><li>assoicate a comment?</li><li>add or link to another post?</li> |
| 11  | Update posts |  The original post can be updated by the author only and the edit history should be visable to other users |
| 12  | Delete posts |  2-Step delete process -1 any user can propose to delete/remove 
| 13  | Content (file management) | Users can upload and download files easily when performing CRUD operations 
| 14  | Search Feature | Users can search by different means<ul><li>basic word or phrase, with ability to use wildcards</li><li>category based filtering</li><li>author based filtering</li><li>date based filtering</li></ul> |
| 15  | User Profiles | Each account has access to a user profile to maintain either a photo and/or avatar/ personal details and preferences.  All resources they interact with on the app have 'foot-print' marking based on profile settings to make it visually easy to see who made the contribution | 



