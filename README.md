## Notes Application

This is a simple notes application built using React. It allows users to create, view, edit, delete, and search notes. The application provides various formatting options for text, such as bold, italic, underline, and alignment.

### Features

- **Create New Note**: Users can create a new note by clicking on the "Create New Note" button. They can enter a title and write their notes in the text area.
  
- **Edit Note**: Users can edit existing notes by clicking on them from the sidebar. The selected note's title and content will be displayed in the text area, allowing the user to make changes.

- **Delete Note**: Users can delete a note by clicking on the delete button next to it in the sidebar.

- **Search Notes**: Users can search for specific notes by entering keywords in the search input field. The application filters the notes based on the search query and displays the matching results.

- **Text Formatting**: Users can format the text in the notes area by applying various styles such as bold, italic, underline, and alignment (left, center, right).

- **Download Notes**: Users can download their notes as a text file by clicking on the download button. This allows users to save their notes locally on their devices.

### Components

- **Notes**: The main component of the application responsible for rendering the entire notes interface.
  
- **Sidebar**: Displays the list of notes along with options to create new notes and search for existing notes.

- **Notes Area**: Provides a text area for writing and editing notes, along with buttons for formatting text and saving notes.

### Usage

1. Clone the repository.
2. Navigate to the project directory.
3. Install dependencies using `npm install`.
4. Run the application using `npm start`.
5. Access the application in your web browser at `http://localhost:3000`.

### Technologies Used

- React: JavaScript library for building user interfaces.
- CSS Modules: For styling components with scoped CSS.
- FontAwesome: For icons used in the application.
- Blob API: For downloading notes as text files.

### Credits

This application is created by Vivesh.

### License

This project is licensed under the [MIT License](LICENSE).
