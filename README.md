# Workshop Maybe Cardano Web Development Course #001

## Most Recent Session (#2): Monday 18 January 2021
- [Meeting Recording on YouTube](https://youtu.be/4Bvq8aIy42Q)
- [Our current "Example App" on GitHub](https://github.com/workshop-maybe/dev-course-001-example-app)

### What we covered:
- Separating components in React (note that we placed all files directly in ```/src``` - this is not the best approach. Even better will be to create sub-folders within ```/src``` to stay even more organized).
- Using ```curl``` to explore API endpoints on the command line
- GET data from [Dandelion API](https://gimbalabs.com/#/open-source-apis) and render it to page
- Using ```map``` to render that data (note that there are more effective ways to handle this data too - this was just an initial look)

### Next Session (#3): Monday 25 January 2021
- Adding some styles to our example-app
    - See how to add Bootstrap to your project: https://create-react-app.dev/docs/adding-bootstrap
- Incorporating the Wolfram API into our example-app
- Moving beyond GET request by taking user input and moving toward interactivity

### To Prepare for Session #3:
- Review video for Sessions [1](https://youtu.be/mFtvVTSzp80) and [2](https://youtu.be/4Bvq8aIy42Q)
- Take a look at the [Wolfram API Docs](https://products.wolframalpha.com/api/)
- Take a look at the [Bootstrap Docs](https://getbootstrap.com/)

---

## Session 1: Monday 11 January 2021
* Lesson 8pm - 9pm; Q&A 9pm - 10pm
* [Meeting Recording on YouTube](https://youtu.be/mFtvVTSzp80)
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
7. External data via Dandelion with ```useEffect``` and ```axios```

---

# Tentative Outline for Sessions 4

## Session 4: Monday 1 February 2021
- Working with your own PostgreSQL database; user authentication
- What do we know so far about oracles?
