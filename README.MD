# QuickNotes

QuickNotes is a small note-taking web app built with plain HTML, CSS and JavaScript. You can write short notes, file them under Personal, Work or Study, search through them and delete the ones you no longer need. Your notes are saved in the browser, so they are still there after you refresh the page.

## Features

- Add notes with a category (Personal, Work or Study)
- Each note shows its text, category label, date/time and a Delete button
- Validation: empty notes and notes over 200 characters show an error message
- Live search that ignores upper/lower case
- Note count that reads correctly for zero, one and many notes
- Notes saved with localStorage and loaded when the page opens
- Colour-coded note cards and a layout that stacks on screens 600px or narrower
- Bonus: "Clear all" button with a confirmation prompt

## How to run locally

1. Clone the repository: `git clone <your-repository-url>`
2. Open the `quicknotes-app` folder.
3. Double-click `index.html` to open it in a browser (no server or install needed).

## What I learned

- How to rebuild a list from an array with a `render()` function, using `createElement` and `textContent` so user text is never treated as HTML.
- How to save and load data with `localStorage`, using `JSON.stringify` and `JSON.parse`.
- How to use Flexbox and a media query to make a form that adapts to small screens.
- How to make small, clear Git commits after each task.