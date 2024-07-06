# Notes Application

This is a simple web-based notes application that allows users to create, edit, and delete notes. The notes are saved in the browser's local storage, so they persist even after the browser is closed.

## Features

- Create new notes
- Edit existing notes
- Delete notes
- Persistent storage using local storage
- Prevents default behavior of the Enter key to insert line breaks

## Technologies Used

- HTML
- CSS
- JavaScript

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/CodeWithMariam/notes-app.git
    ```
2. Open `index.html` in your browser.

## Usage

- Click the "Create Note" button to add a new note.
- Click on a note to edit it. Changes are automatically saved to local storage.
- Click the delete icon to remove a note.

## Code Explanation

- The `notesContainer` element is used to hold all the notes.
- The `createBtn` element is used to create new notes.
- The `notes` variable holds all the notes.
- The `updateStorage` function saves the current state of the notes container to local storage.
- The `showNotes` function loads notes from local storage and displays them.
- Event listeners are added to handle creating new notes, deleting notes, and updating notes in local storage.

## Future Improvements

- Add styling to improve the UI/UX.
- Implement note categorization and searching.
- Add a feature to export notes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

### Related Articles

- [Understanding the HTML5 localStorage API](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)
- [Using localStorage in JavaScript](https://www.javascripttutorial.net/web-apis/javascript-localstorage/)
- [Contenteditable Attribute in HTML](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/contenteditable)
- [Working with contenteditable in JavaScript](https://www.sitepoint.com/quick-tip-editable-content-areas/)
- [Building a Note-taking App in JavaScript](https://blog.logrocket.com/building-a-note-taking-app-with-javascript-and-localstorage/)
