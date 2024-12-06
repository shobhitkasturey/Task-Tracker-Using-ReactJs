# Task Tracker Application

## Overview
The **Task Tracker** application is a React-based project designed to help users manage their daily tasks efficiently. Users can add, edit, mark tasks as complete/incomplete, and delete tasks. The application leverages React's `useState` hook for state management and incorporates a clean and modular component-based architecture.

---

## Features
1. **Add Tasks**: Users can create new tasks.
2. **Edit Tasks**: Update existing tasks with the Edit feature.
3. **Mark as Complete/Incomplete**: Toggle the task status to mark as complete or incomplete.
4. **Delete Tasks**: Remove tasks from the list permanently.
5. **Interactive UI**: Responsive and dynamic user interface with React components.

---

## Project Structure
```
├── src
│   ├── components
│   │   ├── TodoWrapper.js     # Main wrapper component for managing tasks
│   │   ├── TodoForm.js        # Component to add new tasks
│   │   ├── Todo.js            # Component to display a single task
│   │   ├── EditTodoForm.js    # Component to edit an existing task
│   ├── App.js                 # Entry point for the application
│   ├── index.js               # React DOM rendering
│   ├── styles.css             # CSS styling for the application
```

---

## Components

### 1. **TodoWrapper.js**
- Manages the state of tasks.
- Contains logic for:
  - Adding new tasks.
  - Editing tasks.
  - Deleting tasks.
  - Marking tasks as complete/incomplete.

### 2. **TodoForm.js**
- Form component to create new tasks.
- Captures user input and sends the task to `TodoWrapper` for addition.

### 3. **Todo.js**
- Displays individual tasks.
- Includes:
  - Mark as complete/incomplete.
  - Edit and Delete options.

### 4. **EditTodoForm.js**
- Form component for updating an existing task.
- Pre-fills the current task value and updates upon submission.

---

## Installation and Setup
### Prerequisites
- [Node.js](https://nodejs.org/) installed.
- Basic understanding of React.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/task-tracker.git
   ```
2. Navigate to the project directory:
   ```bash
   cd task-tracker
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```
5. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

---

## Usage
1. **Add a Task**:
   - Enter the task in the input field and click **"Add Task"**.
2. **Mark as Complete/Incomplete**:
   - Click on the task text to toggle between complete and incomplete status (A line cuts the task test if marked completed).
3. **Edit a Task**:
   - Click the edit icon (pen) next to a task.
   - Update the task in the input field and click **"Update Task"**.
4. **Delete a Task**:
   - Click the trash icon to remove the task permanently.

---

## Dependencies
- [React](https://reactjs.org/)
- [Font Awesome Icons](https://fontawesome.com/)

---

## Future Enhancements
- Add persistent storage using localStorage or a backend database.
- Include task prioritization and categorization.
- Implement drag-and-drop reordering for tasks.
- Add a search and filter feature.



Enjoy using the **Task Tracker** app! 😊
