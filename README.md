# To-Do List Application

A simple web application to **add, complete and delete tasks**. Tasks are saved in the browser using Local Storage, so they are still there after a refresh.

**Level:** Basic  |  **Project No.:** 5

## Features
- Add a new task (empty tasks are not allowed)
- Mark a task as completed (strike-through style)
- Delete any task
- Filter tasks: All, Active, Completed
- Counter showing how many tasks are left
- "Clear completed" button
- Tasks saved in Local Storage
- Responsive design with automatic light/dark mode

## Folder Structure
```
todo_list/
|-- index.html        -> Main page (HTML + CSS + JavaScript)
|-- README.md         -> Project documentation
`-- images/
    |-- logo.svg      -> Logo shown in the page heading
    |-- favicon.svg   -> Browser tab icon
    `-- banner.svg    -> Banner image for documentation / presentation
```

## Technologies Used
- HTML5
- CSS3 (CSS variables, flexbox, dark mode)
- JavaScript (DOM manipulation, events, arrays, Local Storage)

## How to Run
1. Download or extract the `todo_list` folder.
2. Open `index.html` in any modern browser (Chrome, Edge, Firefox).
3. No installation or internet connection required.

## How It Works
- Tasks are kept in a JavaScript array of objects: `{ text, done }`.
- Every add, complete or delete updates the array, saves it to Local Storage (key: `todo-tasks`) and redraws the list.
- Filters only change which tasks are displayed; they do not change the saved data.

## Possible Improvements
- Edit an existing task
- Due dates and priority levels
- Drag and drop to reorder tasks
