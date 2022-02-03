# CLI Notes App

This is a notes application that runs through the command line built with Node.js. It stores title and body pairs in a json file.

Run `npm install` to load node_modules before running the app.

### To add a note

`node app.js add --title="title" --body="body"`

### To remove a note

`node app.js remove --title="title"`

### To list note titles

`node app.js list`

### To read a note

`node app.js read --title="title"`