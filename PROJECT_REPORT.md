# STUDENT TASK MANAGER
## Flutter Mini Project Report

### 1. Introduction
Student Task Manager is a simple mobile application developed using Flutter and Dart. It helps students maintain a list of academic tasks in one place. Users can add tasks, view them, mark them as completed and delete tasks.

### 2. Problem Statement
Students often need to remember assignments, exam preparation and other academic activities. This application provides a simple interface to record and track those tasks.

### 3. Objectives
- To develop a simple mobile application using Flutter.
- To add and display student tasks.
- To update a task's completion status.
- To delete tasks that are no longer required.
- To understand Flutter widgets and state management.

### 4. Technologies Used
- Flutter: UI framework used to build the mobile application.
- Dart: Programming language used to write the application.
- Material Design: Used for standard UI components and styling.
- StatefulWidget and setState: Used to refresh the screen when task data changes.

### 5. Modules
1. **Home screen:** Displays the application title and task summary.
2. **Add task:** Opens a dialog where the user enters a task.
3. **Task list:** Displays all tasks using ListView.builder.
4. **Complete task:** Checkbox changes a task between completed and pending.
5. **Delete task:** Delete icon removes a task from the list.
6. **Task summary:** Shows total, completed and pending task counts.

### 6. Working Procedure
1. The application starts from the main() function.
2. MaterialApp loads the TaskHomePage.
3. The home page displays sample tasks and their counts.
4. The user presses Add Task and enters a task name.
5. The task is added to the list using setState().
6. The user can select the checkbox to mark a task completed.
7. The user can press the delete icon to remove a task.
8. The summary counts update whenever the list or task status changes.

### 7. Widgets Used
- MaterialApp: Root widget of the application.
- Scaffold: Provides the basic screen structure.
- AppBar: Displays the application title.
- Column and Row: Arrange widgets vertically and horizontally.
- Card: Displays task information in a card.
- ListView.builder: Builds the task list.
- ListTile: Arranges each task row.
- Checkbox: Changes task completion status.
- TextField: Accepts a new task.
- AlertDialog: Displays the add-task form.
- FloatingActionButton: Opens the add-task dialog.

### 8. State Management
The project uses StatefulWidget and setState(). When a task is added, deleted or marked as completed, setState() tells Flutter to rebuild the affected UI using the updated data.

### 9. Testing
- Add a task with valid text: The task appears in the list.
- Submit an empty task: No task is added.
- Select a checkbox: The task is marked completed.
- Delete a task: The task is removed.
- Update task status: The summary counts are recalculated.

### 10. Limitations
This is a mini-project demonstration. Tasks are stored in an in-memory list and are not saved permanently. They reset when the application restarts. The project does not include login, database or cloud synchronization.

### 11. Future Enhancements
- Store tasks permanently using SQLite or Firebase.
- Add task due dates and reminders.
- Add categories such as assignments and exams.
- Add user login and cloud synchronization.

### 12. Conclusion
Student Task Manager demonstrates how to build a basic interactive mobile application using Flutter and Dart. It provides task creation, display, completion and deletion features. The project also demonstrates commonly used Flutter widgets, layouts and basic state management.
