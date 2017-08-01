# Static Web Group Project

As a team, build the web site for a fictitious product company. The team gets to decide what the name of the company is, and what types of products it manufactures. Be creative and have fun.

## Requirements

### Theme

Pick a theme that the team likes. A good place for inspiration is the [Wordpress themes](https://wordpress.org/themes/) site. Do not purchase, or copy the theme code, just browse them for inspiration. Everyone should agree on a theme and ensure that each page is consistent with the colors, fonts, and/or images chosen.

### Pages
Each team member is going to be responsible for the content of a different page, so decide on the name and content for each of those pages. Some possible options are...

1. Home page
1. Company history
1. Company culture/mission
1. Job listings
1. Company awards

Regardless of what pages each team member works on, each team must have a Products page and an Employee page for their site that the team will collaborate on. See more details about the product page below.

### Git
Your team is going to learn how to use git to enable good teamwork when building a software product.

1. Now that everyone has joined the same team, everyone clone the Github Classroom project into your current directory - which should be `groupprojects` if you ran the setup commands.
1. `cd` into the directory that got created.
1. Before anyone on the team writes a single line of code, the team will decide on a branch naming strategy. Branches should be descriptive of the work that is going to be done on that branch. Some teams also decide to add the developer's information to the branch name, such as initials. For example, a developer named Jasmine Sheboygen is going to work on the job listings page for the web site. A good name for the branch would be `js-job-listing-page`.
1. Again, before you write any code, one team member volunteer to create the  ignore file on a branch.
    1. `touch .gitignore`
    1. `git add .gitignore`
    1. `git commit -m "Initial commit with .gitignore file"`
    1. `git push origin YOUR BRANCH NAME`
1. Now make a PR and get your team to approve it :+1: and merge into master on GitHub.
1. Now everyone should `git pull origin master` (from their local master branch).
1. That's the last commit you make on the master branch. At this point, each teammate will create their branch.

Now everyone will work on their page on those individual branches. Once a teammates feels that their work is complete, the teammate will push up their branch to Github and create a pull request. One of the other teammates must review the pull request and give a thumbs up (Just type :+1 in the comment box).

Once the PR gets a thumbs up, the teammates should merge the current version of master (the one with all their teammate's fancy additions) to their current working branch by following this process:

```bash
# You will be doing this from your working branch, for example: js-job-listing-page
# Check to make sure that your working tree is clean. Add and commit all that you need to.
git pull origin master
# Fix any merge conflicts, if you have them
# git add and git commit any files affected by the merge conflict.
```

Now you have all of your work, plus all of your teammate's approved work on one branch. :cool:

### Product page

The team's product page will be driven from JavaScript code. Decide on the names of, at least, 8 products that your business manufactures. The product page must have a linked JavaScript file.

- [ ] Create an array to hold your products.
- [ ] Each item in the array must be an object that contains the following information: name, description, price, and URL for product image. You can add more properties if that's what the team wants, but it must have those.
- [ ] The team will use JavaScript to add each product to the DOM.
- [ ] Each product must be a card, much like everyone made in the Static Web quiz. As a team, decide on the style of the card.
- [ ] The layout of the product page should be a grid of cards. 3-wide, 4-wide, 5-wide, the teams must decide how many cards are on each row.

### Employee page

- [ ] Create an array of 3 employees. Each employee should be an object. The object should have at least 4 key/value pairs: 
    - Employee Name
    - Employee Title
    - Employee Image
    - Employee Bio
- [ ] Create a function to add a new employee. This function should accept 4 arguments: employee name, employee title, employee image and employee bio. This function should add the employee as an object to the employee array.
- [ ] Call the createEmployee function twice, adding 2 more unique employees.
- [ ] Loop through the array of employees and print them to the page. 
- [ ] The layout of the employee page should be a grid of cards. 3-wide, 4-wide, 5-wide, the teams must decide how many cards are on each row.

