# Workshop Maybe Cardano Web Development Course #001

## Session 1: Monday 11 January 2021
* Lesson 8pm - 9pm; Q&A 9pm - 10pm
* Google Meet (link to follow)
* [Join the conversation on Discord](https://github.com/workshop-maybe/dev-course-001)

### Pre-Reading
- Take a look at [CSK 003](https://github.com/GimbaLabs/csk-003), in particular Part 3. At minimum, make sure to set up Visual Studio Code and NodeJS.
    - [Visual Studio Code](https://code.visualstudio.com/)
    - [Node.js tutorial in Visual Studio Code](https://code.visualstudio.com/docs/nodejs/nodejs-tutorial)
    - [Direct link to Node.js](https://nodejs.org/en/download/)
- If you want to get a head start, read the official documentation about JavaScript Objects. This will help to provide context for what you'll see on Monday night.
	- https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics 
	- https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON

### Links (coming soon)
- Our working app
- ideas.json

### Session Outline
1. Create our React Project 
    ```npx create-react-app course-app```
2. JavaScript Keyword: ```import```
3. What is the role of ```App.css```?
4. JavaScript Object Notation (JSON)
5. Using data in our app
    ```<p>{ideas.idea[0].id}: {ideas.idea[0].text}</p>```
6. ```array.map```
7. External data via Dandelion

### Follow Up Assignment
Use Bootstrap to improve the appearance of our site
1. Styling via Bootstrap
	1. See how to add Bootstrap to your project: https://create-react-app.dev/docs/adding-bootstrap
	2. Read documentation here: https://getbootstrap.com (you probably installed v4.5.3?)
2. A different endpoint?

# Tentative Outline for Sessions 2-4
## Session 2: Monday 18 January 2021
Separating concerns in React and using React Router; More Dandelion queries; GET vs POST requests

## Session 3: Monday 25 January 2021
Working with your own PostgreSQL database; user authentication

## Session 4: Monday 1 February 2021
What do we know so far about oracles?
