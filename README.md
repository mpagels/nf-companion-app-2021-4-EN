# companion app

## Task

Your goal is to create a mobile web application for the student companion app

- Mobile only
- Work in teams, help each other!
- Pair programming: always 2 or 3 working together (3 in the case of the team of 5). Drivers and Copilots
- Github Workflow: work in feature branches, as we explained. Use the following naming for your branches feat/name-of-your-feature (e.g. feat/add-dashboard-screen
- HTML + CSS
- Build after design (pixel perfect)

At the end your project strucutre should look like this:

```
student-companion-app
├── .git
├── .gitignore
├── node_modules
├── package-lock.json
├── package.json
├── design
    ├── icons
    ├── screens
    ├── file
    └── other-file
├── README.md
└── src
    ├── index.html
    ├── bookmarks.html
    ├── profile.html
    ├── create.html
    └── css
        ├── style.css
        ├── base.css
        ├── colors.css
        └──  ...<other.css> files
```

## _Tips_

### GitHub Flow

- Use the template to create a repository for your team
- Organise yourselves, which team does what
- Each pair in your team should work on a Feature Branch
- Communicate!

### Work in Teams

- Find possible flaws to discuss with the coaches
- Help each other! Also people from other teams. This is not a competition.
- You can create a private channel for communication in Slack per team.

### HTML + CSS

- Use semantic HTML (use MDN to search the elements)
- Avoid unnecessary elements
- Organize your CSS in a good way! Align with the team and then keep being consistent!
- Deploy your website with Vercel, and test it on a real phone!  
  <br>

## Design Files

See it online in [Sketch Cloud](https://www.sketch.com/s/4b6ce9a7-f7b8-4bd1-a5ac-f8a8a924be3e).

Images of each screen, the .sketch file, and all the icons can be found in the design folder

## How to get started:

1. use the `template` function to make your own copy of this repo
1. `clone` the repo to your local machine
1. `cd` into the folder
1. run `npm install` to install dependencies
1. to get a live version of your website pls use `Live-Server`

With `npm install` you installed `htmlhint`. To use it correctly you need to be shure you have installed the [vscode extension](https://marketplace.visualstudio.com/items?itemName=mkaufman.HTMLHint)

## Branch naming conventions

We name branches in this style: `<type>/<name>`

where `<type>` is one of the following

- feat for features that implement a user story
- task for technical tasks / debts
- fix for bug fixes

and `<name>` is a short description.

### Examples:

```
refactor/form
fix/incremental-static-regeneration
hotfix/cta-button
```

We will use the `main` branch as the `production` branch. So the `main` banch holds the current working version of the project. Do not develop in this branch. Branch from it and create a pull request to merge your new added code to the `main` branch.

## Commits

> A well-crafted Git commit message is the best way to communicate context about a change to other developers working on that project, and indeed, to your future self. [Source: freecodecamp](https://www.freecodecamp.org/news/writing-good-commit-messages-a-practical-guide/)

- A commit message should be a capitalized, short (~72 characters or less) summary of the introduced changes
- Write your commit message in the imperative: "Fix bug" and not "Fixed bug" or "Fixes bug."

### _Examples_:

```
Add missing url to register form Button
Update docker runner image to python 3
```

#### Once a step is finished:

1. `push`,
1. create a pull request on GitHub (maybe share it and get a review, definitely do a review for yourself),
1. `merge`,
1. synchronize your local machine and move to the next branch

### Pull request

[Very good article about how to write good pr messages](https://www.atlassian.com/blog/git/written-unwritten-guide-pull-requests)
