# Notetaking app

Work in progress.

Run the backend with `DATABASE_NAME=database.db go run src/main.go` and upload the files with the `index.html` page from the backend folder.
Run the frontend with `npm run dev`.

To-do:

- Allow user to save the file to the server with CTRL+S.
  - Create a function and route to edit the filecontent.
- Fix the last test function for the database.

Think about a solution for:

- User duplicating a file (we can't have the same filepath, if he edits one of them).
