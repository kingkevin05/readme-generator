# README.md
  ![Badge for GitHub repo top language](https://img.shields.io/github/languages/top/kingkevin05/readme-generator?style=flat&logo=appveyor) ![Badge for GitHub last commit](https://img.shields.io/github/last-commit/kingkevin05/readme-generator?style=flat&logo=appveyor)
  
  badges hosted by [shields.io](https://shields.io/).
  
  
  ## Description 
  
  A good project/app should come with a quality README that  informs the user about the app. whats its for, how to use it, how to install it, and how to make contributions so that other developers are more likely to use and contribute to the success of the project.
  
  This is a command-line application that runs with Node.js that dynamically generates a README.md file based on input about your project.
  
  ## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  
  ## Installation
  
  
  To generate your own README, first run npm install in order to install the following npm package dependencies as specified in the package.json:

* [`inquirer`](https://www.npmjs.com/package/inquirer) that will prompt you for your inputs from the command line

* [`axios`](https://www.npmjs.com/package/axios) to fetch your info from the GitHub API

Run the app with with `node index.js.`
  
  ## Usage 
  
  *Instructions and examples for use:*
  
When you run `node index.js`, the application uses the `inquirer` package to prompt you in the command line with a series of questions about your GitHub and about your project.

The application takes your answers and uses `axios` to fetch your GitHub profile from the [GitHub API](https://developer.github.com/v3/), including your GitHub profile picture and email.
From there, the app will generate the markdown and a table of contents for the README conditionally based on your answers to the Inquirer prompts. If you don't answer the optional questions, that section will not be included in your README. 

The README will also include badges.

Finally, `fs.writeFile` is used to generate your project's README.md file.
  
  ## License
  
  MIT License
  
  ---
  
  ## Questions?
  
  ![Developer Profile Picture](https://avatars.githubusercontent.com/u/75460766?v=4) 
  
  If you have any question please feel free to reach out:
 
  GitHub: [@kingkevin05](https://api.github.com/users/kingkevin05)
  
