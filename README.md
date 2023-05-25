# Note Taker

Note Taker is a simple web application that allows users to create and save notes. The application uses Express.js for the server-side code and interacts with a JSON file (`db.json`) to store and retrieve notes.

## Installation

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the dependencies by running the following command:
   ```shell
   npm install

## Usage

Start the application by running the following command:

Copy code
node server.js
Open your web browser and visit http://localhost:3001 to access the Note Taker application.

## Homepage

The homepage (/) displays the landing page of the application with a brief introduction.
Click on the "Get Started" button to navigate to the Notes page.

## Notes Page

The Notes page (/notes) displays the existing notes and allows users to create new notes.
To create a new note, enter a title and the note content in the provided input fields.
Click the save button (disk icon) to save the note.
The saved notes are displayed on the left-hand side of the page.
Click on a saved note to view its content.
To create a new note, click the pencil icon.

## API Routes

The application provides the following API routes:
GET /api/notes: Retrieves all the saved notes from the db.json file.
POST /api/notes: Creates a new note and saves it to the db.json file.

## Technologies Used

Express.js: Fast, unopinionated, minimalist web framework for Node.js.
path: Node.js module for working with file and directory paths.
fs: Node.js module for interacting with the file system.
uuid: Node.js module for generating unique IDs.