# Project Tasks

- [ ] Plan your project

    - Visualize your end result. What is it built with? What can it do? Make sure that it satisfies all of the project objectives.

    - Make a timeline for yourself and avoid the temptation to build things that aren’t required. Setting firm boundaries and deadlines will keep you on track and prevent [scope creep](https://en.wikipedia.org/wiki/Scope_creep).

    - The following tasks will help you identify natural break points.

- [ ] Wireframe your application

    - Using pencil and paper, or a wireframing software of your choice, draft what you’d like your application to look like.

    **Hint**

    Think about what the main components of the site will be and how you would like to see them arranged on the page. You should also think about the user flow and design all of those states and transitions as well. Don’t forget about error states!

    You should also think about:

    - The application’s color palette
    - How to break up your design into components
    - How your application will look at different screen sizes

- [x] Create files and run it locally

    On your computer, create the files needed for your React application. Run your application locally to see what it looks like in the browser.

    **Hint**

    You can use [create-react-app](https://create-react-app.dev/) to start your React application. If you want to set up Redux automatically, you can use [the Redux flag](https://redux-toolkit.js.org/introduction/quick-start#using-create-react-app).

- [x] Version control

    Set up the folder you created previously to be a Git repository. Push the initial files to a repository on GitHub. You should be consistently committing your changes throughout the project. Make sure to have meaningful commit messages.

    **Hint**

    To initialize your Git repository, you can run the below code in your terminal, where `application` is the name of your project folder.

    `git init application`

    If you want a refresher on the syntax, look back at the [Git cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf).

- [ ] Build the components

    Based on your wireframes, start building your application with fake, local data. Remember to build reusable components and to keep your components small.

    Other things to keep in mind:

    - Your application should work for all screen sizes
    - You are welcome to use libraries to help you accomplish features
    - You should write unit tests and end-to-end tests where it makes sense

- [ ] Add Reddit data

    Connect your application to the Reddit API.

    When interacting with the API, don’t forget to handle error states.

    Make sure you set up your app to handle errors related to the API rate limits (as mentioned in the **Setup** tab). See the Hint for ideas!

    **Hint**

    A few ways to work within the rate limits:

    - cache the results of some successful queries, then show those when a query fails
    - look for ways to reduce the overall number of queries being made
    - provide a front-end error to the user that new data could not be loaded

- [ ] Publish to the web

    Congratulations on building your application! Deploy what you’ve built and share it with the world!

    **Hint**

    There are many ways to deploy your application online, including GitHub Pages and Netlify.

- [ ] Next steps

    Go back to the project requirements section and complete the optional requirements.

