# nodejs-notes-app

## This is a terminal running note app written in nodejs.

Clone the repository and run npm install in the repo folder.

Make sure you have installed nodejs on your machine.

With several terminal commands you can create, remove, read and list your notes.

By adding a note for the first time the app will create a notes.json file where your notes will be stored.
<br />
<br />

### Add a note

Terminal:
`node app.js add --title="Your note title" --body="Your note body" `
<br />
<br />

### Remove a note

Terminal:
`node app.js remove --title="note title to remove" `
<br />
<br />

### Read a note

Terminal:
`node app.js read --title="note title to read" `
<br />
<br />

### List a note

Terminal:
`node app.js add list `
