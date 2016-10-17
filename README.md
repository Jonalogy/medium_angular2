#Make a Medium
The challenge is to build a basic version of [medium](https://medium.com) using a frontend framework.
It should be approached in iterations, details of which are below.
The emphasis is on learning the framework, so focus on understanding (i.e. don't implement anything you don't understand).

### Domain Model
The Domain Model is simple.
1. It should just be an Article (title, description).
2. Add a User model, so a user has many articles.

### API
The API can be built in any technology, keep it simple.
1. Full RESTful CRUD functionality for Articles
2. Authentication for Users. Everyone can READ. Only an Authenticated User can CREATE. Only an owner can UPDATE and DELETE.

### Frontend
The frontend should be the focus. Although don't obsess over the CSS, you can use a framework like Bootstrap.
1. SPA with full CRUD functionality for Articles (including Client-Side validation). Should be a Master-Detail View ie. list a snippet of an article and then load the full detail when the user clicks 'read more' - this should be a separate API call to the show endpoint.
2. Add Ability to Register and Login a User (include Client-Side validation).
3. Add Routing to update the browser URL.

### Presentations
Each Group (excluding Instructors) will teach a half-day class on the framework. It should include
- the philosophy of the framework
- it's strengths and weaknesses
- A getting started code along
