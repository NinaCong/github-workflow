# Github Workflow and Setup
Each year, to allow Cherubs to program their own interactive graphics and site designs, we use Github to publish their work and embed it into our Wordpress site. This allows maximum flexibility, ease of editing, and the least probability of accidentally breaking the main Cherubs site.

## Github Training
On Sunday or Monday, hold a brief Github training session teaching the Cherubs how to use Github. Have them:
- Setup new Github accounts.
- Verify their emails.
- Create a new repo.
- Create a gh-pages branch.
- Create an index.html page with any HTML they'd like.
- Lookup the URL of their new website in their repo settings.

## Overall Setup
- [Create a new team](https://github.com/orgs/medillcherubs/new-team) for this year's Cherubs. Name the team based on the current year, for example `Cherubs 2017`. Make the team secret. ([See teams from past years](https://github.com/orgs/medillcherubs/teams))
- Assign one of the tech team captains to gather everyone's Github usernames and add them to the new Cherub team. You can also add them yourself.
- [Create a second team](https://github.com/orgs/medillcherubs/new-team) for this year's CAs and Instructors, or anyone who will need admin access to every project for editing. Name the team something like `Cherubs 2017 Admin`. Make the team secret.
- Find out which CAs will be staying behind to help Roger do one last edit of the website and make sure they have a Github account and are on the Admin team.

## Creating a Repo
When a Cherub is ready to put their work on Github, follow these procedures:
- Create a new repository and name it using this current year and their project slug. For example: `2016-cherub-timeline`. Initialize the repo with a README.
- Create a new branch named `gh-pages`.
- Go to the repo settings, go to **Branches** and change the default branch to `gh-pages`. Still within the repo settings, go to **Collaborators and Teams** and add the Cherubs team you've just made as Read status, and the Admin team you've just made as Admin status.
- Directly add the Cherub working on this project as a collaborator.
- Following [this README template](README-template.md), edit the README file for the repo with the relevant information.
- Create a new index.html file by [copying this template](index.html).
- Have the Cherub put all their code into their new index.html file.
- Have the Cherub follow the instructions in their new README file, and post their work into a Wordpress post.

## Documentation
Somehow other than the Tech team agents will be editing the content of the interactives later. Make sure they know where they can edit each project. 
- Create a Google Doc, shared with all the instructors and CAs, with a list of repositories from this year.
- For each project, write the name of the project, such as "Cherub World Records" and then include a direct link to the URL that allows someone to edit that project's index.html file.
