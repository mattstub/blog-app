# Blog App
Develop a blog application that will allow you to publish posts you write to the internet.  

### Technical Specifications
- [ ] Project generated from Express
- [ ] Handlebars (HBS) as view engine
- [ ] NODEMON as Development Server `npm dev`
- [ ] FOREVER as Production Server `npm prod`
- [ ] Hosted on Heroku
- [ ] Reboot of server loads default article from **Articles Resource**
- [ ] Utilize CI to deploy changes to Production Server

### Article Specifications
We will create an Article Resource with the following fields:
  - [ ] Title
  - [ ] Author
  - [ ] Date Created
  - [ ] Date Published
  - [ ] Draft (true or false)
  - [ ] Body (markdown version of post)

### User Stories
- [ ] As a reader, I can see a list of articles when I visit the homepage `/`
- [ ] As a reader, I can see an about page when I visit `about`
- [ ] As a reader, I can see a page with a list of projects with I visit `/projects`
- [ ] As a reader, I can click on an article from the homepage and view an article
- [ ] As a reader, I can visit an article `/articles/:id` where ID is the ID of the article
- [ ] As an author, I can visit an unlisted page called `/manage` (this will eventually be the login page)
- [ ] As an author, I can visit an unlisted page called `/manage/articles` and see a list of articles
- [ ] As an author, I can visit `/manage/articles/edit/:id` and edit an existing article
- [ ] As an author, I can clik on an `add` button that will allow me to add a new article
  - [ ] This will first take me to a form `/manage/articles/new` with all required fields to create an article
  - [ ] Once completed and `save` is clicked, it will redirect me back to `/manage/articles`
  - [ ] Article just created should be visible
- [ ] From the article list, I can click to edit an article, which takes me to `/manage/articles/edit/:id`
- [ ] From the article list, I can click on a `delete` action, which will prompt before deleting
  - [ ] `Yes` will delete the article
  - [ ] `No` will cancel the action
- [ ] From this list I can click `view` which links me to the article in `read only` mode

### Versions
- [ ] Version 1.0.0 - Will involve memory only storage
- [ ] Version 2.0.0 - Will introduce database to persist any changes
- [ ] Version 3.0.0 - Will introduce user authentication
- [ ] Version 4.0.0 - Rebuild API with Vue.js and Koa.js