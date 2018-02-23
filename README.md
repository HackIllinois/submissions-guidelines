# Submissions Guide
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)

Ping @rishidesai or @narendasan in #submissions-questions on the [HackIllinois 2018 Slack](hackillinois-2018.slack.com) with any questions

## Your DevPost Submission

### Create a project on devpost [HackIllinois 2018 devpost](http://go.hackillinois.org/devpost2017)

- Briefly fill out the description. (All other sections are up to your discretion.)
- __Make sure to include a link to your source code repository in the "try it out" section__
- If you are submitting to any particular prizes, make sure to describe why you believe your submission is eligible, and also mark them on your submission.
- Then follow the instructions below to complete your submission depending on whether you [contributed to an already existing project or repo](#if-you-contributed-to-an-already-existing-project-repo) or [you created a brand new repo to host your work](#if-you-started-something-new-new-repo)

### [If You Contributed to an Already Existing Project (Repo)](#contribute)

In addition to the content above, we also would like you to link a GitHub gist with some additional information in your devpost submission.

#### Gist Content
There are two cases:

1. You did not complete a PR:

   That's totally okay! You do *not* have to finish a PR to submit to HackIllinois. In your submission gist, please link to any work-in-progress code (a branch, forked repo, etc.) along with the content covered below.

2. You completed a PR:

   Awesome! In your gist, please link to your PR and also make sure you're following the contribution guidelines to the repo you are submitting your pull request to. 


In both cases, we'd like you to include the following (in addition to any links) in the submission gist:

- Issue(s) that you chose to work on.
- Explanation of your decision making on approaching the issue
- Discussion of your contribution's current status in the pipeline and what is remaining (if there is anything).
- Credit others contributors (teammates with what each person worked on, mentors, etc.).

##### Examples:

- submission gist: https://gist.github.com/narendasan/a6450bc86c7a97b1cfffeea84f92d118

for completed PR: https://github.com/Homebrew/brew/pull/1312 

Be prepared to talk about how the specific contribution process for your project played a role in the development of the contribution. If your PR was merged in and you had to make edits in your contribution before it was approved, explain what was changed and why.

### [If You Started Something New (New Repo)](#create)
If your code is hosted in a new repo, your submission should consist of a [devpost](https://hackillinois-2018.devpost.com/) submission linking to your public code repository which should include at least four specific files: README.md, LICENSE (there maybe cases where this is not applicable, if so tell us the reason in your devpost submission), CONTRIBUTORS.md and CONTRIBUTING.md. 

#### 1. README.md [Template](https://github.com/HackIllinois/Submissions-Guidelines/blob/master/templates/README_TEMPLATE.md)

- A __technical description__ of what your project is (functionality, purpose - if any, etc.)
- Instructions on how to build, install, and use your project
- A link to the Contributors Guide

   ##### Examples:

   - https://github.com/rstacruz/hicat
   - http://svn.apache.org/repos/asf/httpd/httpd/trunk/README
   - https://github.com/python/cpython
   - https://github.com/airbnb/lottie-ios
   - https://github.com/hackillinois/api-2017
   - https://github.com/rust-lang-nursery/rust-cookbook

#### 2. LICENSE

- Add a license to your repository using an [OSI approved License](http://opensource.org/licenses)

#### 3. CONTRIBUTORS.md

- Enumerate who was on your team, their emails, who implemented what in the project and any mentors or other significant members of the group

#### 4. CONTRIBUTING.md [Template](https://github.com/HackIllinois/Submissions-Guidelines/blob/master/templates/CONTRIBUTING_TEMPLATE.md)

- __Create a Contributing Guide__
- Explain the process of getting code merged into master to make it easier for contributors to submit additions to your project

  ##### Examples

  - https://github.com/Homebrew/homebrew-core/blob/master/CONTRIBUTING.md
  - https://github.com/rust-lang/rust/blob/master/CONTRIBUTING.md
  - https://github.com/redox-os/redox/blob/master/CONTRIBUTING.md
  - https://github.com/rust-lang-nursery/rust-cookbook/blob/master/CONTRIBUTING.md

##### *Bonus:*

- Create comprehensive set of __issues__ to represent future features and/or current bugs
- __Incorporate tests__ into your project
- Provide a link to a __packaged release__
- Proper use of source control


## Expo

### Be ready to explain during the project expo:

- __Thought process and inspiration__ for your project
- __Potential uses and benefits of your project__ 
- __Issues__ you faced
- __Major decision making__, such as the selection of technical frameworks, languages, code structure, etc.
- Your selection of __FOSS license__ in your README.md
