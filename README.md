![cf](https://i.imgur.com/7v5ASc8.png) Lab 33: Middleware - Budget Tracker
======

## Submission Instructions
* Continue working on the fork that you created yesterday
* Create a new branch for all of today's code
* Write all of your code in a directory named `lab-` + `<your name>` **e.g.** `lab-susan`
* Open a pull request to this repository
* Submit on canvas a question and observation, how long you spent, and a link to your pull request

## Configuration
Configure the root of your repository with the following files and directories. Thoughtfully name and organize any additional configuration or module files.
* **README.md** - contains documentation
* **.gitignore** - contains a [robust](http://gitignore.io) `.gitignore` file
* **.eslintrc.json** - contains the course linter configuration
* **.eslintignore** - contains the course linter ignore configuration
* **.babelrc** - contains babel config
* **package.json** - contains npm package config
* **webpack.config.js** - contains webpack config
* **src/** - contains the frontend code
* **src/components/** - contains your components
* **src/main.js** - contains the entire app
* **src/style** - containing your `.scss` partials and styles
* **src/style/main.scss** - contains the entry point for `.scss` partials

## Feature Tasks
##### Minimum Requirements

### Complete Your App Functionality
* Complete all remaining lab 31 and 32 feature tasks
* Add `reporter` middleware to your application's redux store
* Add custom validation middleware to your redux reducers

### Components
Upon completion of this application, your component hierarchy should be as follows:
```html
<App />
  <Provider /> 
    <BrowserRouter />
      <Dashboard />
        <CategoryForm />
        <CategoryItem />
          <CategoryForm />
          <ExpenseForm />
          <ExpenseItem />
            <ExpenseForm />
```
