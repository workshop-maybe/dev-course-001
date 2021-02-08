# Workshop Maybe Web Development Course #001
THANK YOU to everyone who has particpated, dropped by, reviewed what we've got here for this first "dev course" experiment. I have learned a lot, and I hope you've learned a bit too.

Two specicific lessons I've learned:
1. It's really tempting to try to pack an agenda and show off a variety of functionality at once!
2. Making sure there's time to get stuck, and to engage in collaborative problem solving is an effective way to use in-person time.

I'd like to get better at scoping our work so that I can convey a few important ideas in a way that makes it feel natural for people to go off and tinker for a few hours. For the next iteration, my goal is to create a course where someone with limited time will be able to get value out of just one live course per week plus two hours of individual work time (ie, just a cut of your Netflix time, but still enough time to relax). And for anyone who has more time, I want to get you right to edge of the rabbit hole so you can jump in.

So "Version 2" of this course is coming soon! But first, let's finish up with one more meeting this Monday. I want to get everyone to the point of understanding the benefits of what we'll do in v2.

### To Prepare for Session #4 on Monday 1 February 2021:
- Review video for Sessions 1-3 below
- Read/work through a bit of [the React tutorial](https://reactjs.org/tutorial/tutorial.html). In particular, pay attention to the parts about "State".
- If you've already completed this tutorial on your own, take a look at [Components and Props in the React docs](https://reactjs.org/docs/components-and-props.html), and continue on to [State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html).

---

### Most Recent Session (#3): Monday 25 January 2021
- [Meeting Recording on YouTube]()
- [Our current "Example App" on GitHub](https://github.com/workshop-maybe/dev-course-001-example-app)

### What we covered:
- Getting even more organized with ```react-router-dom```
- Adding some styles to our example-app
    - See how to add Bootstrap to your project: https://create-react-app.dev/docs/adding-bootstrap

### What we didn't get to:
- Incorporating the an external API into our example-app (sorry - no Wolfram tonight, but soon!)
- Reasoning about the role of oracles in a DApp

### Further Reading
- Read this [wikipedia entry about the Document Object Model](https://en.wikipedia.org/wiki/Document_Object_Model)
- Take a look at the [Bootstrap Docs](https://getbootstrap.com/)

---

## Session 2: Monday 18 January 2021
- [Meeting Recording on YouTube](https://youtu.be/4Bvq8aIy42Q)

### What we covered:
- Separating components in React (note that we placed all files directly in ```/src``` - this is not the best approach. Even better will be to create sub-folders within ```/src``` to stay even more organized).
- Using ```curl``` to explore API endpoints on the command line
- GET data from [Dandelion API](https://gimbalabs.com/#/open-source-apis) and render it to page
- Using ```map``` to render that data (note that there are more effective ways to handle this data too - this was just an initial look)

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
