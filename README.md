# Sprint Challenge: User Interface and Git - Multi-Page Website

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored User Interface and Git. During this Sprint, you studied Semantic HTML, CSS Fundamentals, CSS Flexbox Module, and Git. In your challenge this week, you will demonstrate proficiency by creating a multi page website that has some missing HTML elements as well as CSS specificity problems that need to be solved.  You will also create an additional web page that will be linked to from a navigation you will build.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. Your work reflects your proficiency in user interface and your command of the concepts and techniques in semantic HTML, CSS fundamentals, CSS flexbox module, and git.


## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons)

## Description

In this challenge, you build a missing header (navigation and image) on the home page, update some CSS styling on the home page, and create an additional page (About) which will link from the navigation you created.

In meeting the minimum viable product (MVP) specifications listed below, your web page should look like the solution screen shots of the home and about pages (found in the design-files folder):

[Click here for the home page example](https://tk-assets.lambdaschool.com/39a49225-8ac9-43da-aa90-514fd60ae99a_sprint-challenge-ui-home-example.png)

[Click here for the about page example](https://tk-assets.lambdaschool.com/ede1bb1a-63ff-4801-8c02-3efa2f603190_sprint-challenge-ui-about-example.png)

## Self-Study Questions 
### (please edit this file and write your answer below each question. In addition, you may also review these questions with your mentor)

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. If you were to describe semantic HTML to the next cohort of students, what would you say?
 - Semantic HTML labels page sections according to what they are, so it is clear to browser and developer what content is contained within. This gives a clear structure to the page and eliminates unclear and nondescriptive tags, such as <div>. Semantic HTML is a best practice when coding modern websites. It is also helpful for accessibility because screen readers they can better understand what the stuff is.

2. Name two big differences between ```display: block;``` and ```display: inline;```.
 - display:block is displayed as a block and has some built in whitespace, while display:inline is displayed on the same line, without the boxy structure.

3. What are the 4 areas of the box model?
 - Margin, Border, Padding, Content

4. While using flexbox, what axis does the following property work on: ```align-items: center```?
 - the x-axis (horizontal)

5. Explain why git is valuable to a team of developers.
 - Git is a version control system and is valuable to developers because it allows everyone to work on the latest version of a project's code. It allows developers to work on their own separate "branches" and push code changes in without immediately overwriting work that already exists. It also allows for the team to pick and choose which code to accept to their master branch (latest master version of the code) and allows them to revert changes if there are bugs.
 
You are expected to be able to answer all these questions. Your responses contribute to your Sprint Challenge grade. Skipping this section *will* prevent you from passing this challenge.

## Project Set Up

- [X] Create a forked copy of this project.
- [X] Clone your OWN version of the repository (Not Lambda's by mistake!).
- [X] Create a new branch: git checkout -b `<firstName-lastName>`.
- [X] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly.
- [X] Push commits: git push -u origin `<firstName-lastName>`.
 
Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**



## Minimum Viable Product

Your finished project must include all of the following requirements:

### Home Page

[Review the provided design file for the home page](design-files/home.png).  Notice the navigation and header images are missing.

* [X] Build the HTML and CSS to create the missing navigation and header.
* [X] Link the `About` navigation item to the [about.html](about.html) page

You will also notice there are 10 boxes on the home page that need background colors.  Use this list below to correctly style each box (Note: inline styles are not acceptable. All styles should be written in your index.css file):

* [X] box1: `teal`
* [X] box2: `gold`
* [X] box3: `cadetblue`
* [X] box4: `coral`
* [X] box5: `crimson`
* [X] box6: `forestgreen`
* [X] box7: `darkorchid`
* [X] box8: `hotpink`
* [X] box9: `indigo`
* [X] box10: `dodgerblue`

### About Page

[Review the provided design file for the about page](design-files/about.png). You have been provided the HTML wrapper, footer, and page content for the about page. Create the rest of the missing HTML and CSS to match the design file.

* [X] Copy and paste your home page navigation and header into the about page
* [X] Update the header image with the about page image
* [X] Link the `Home` navigation item back to the `index.html` page.
* [ ] Build the rest of the about page layout to match the design

In your solution, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

Note: Please make sure you are using flexbox to layout your website. Floats, inline-block, tables, etc, should not be used for layout. 

## Submission Instructions 
 
Please submit the url to your pull request in Canvas
