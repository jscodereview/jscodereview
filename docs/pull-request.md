# Problem

All of the application code was in one file.

# Solution

Break up the single file into modules; use ES6 `import` statements to load individual modules, and use [Babel](https://babeljs.io/) and [webpack](https://webpack.github.io/) to generate the runtime code.

# See it work

Check out the branch for this pull request, run `npm install` to get the latest modules, then run `npm start` to start the webpack development server. Visit http://localhost:9000 to see the application load.

(I've also added these instructions to the README.)

# Discussion

- This was my first time using webpack, and it was hard! I probably got some things wrong, I'd be really interested in feedback on my webpack config.
- I broke up the single application file where it was easy to break it up; I could probably break it up better, so guidance there would be great.
- I know I still need to add some linting to this, because I noticed some discrepancies in my code style, but I wanted to put that in a separate pull request.
