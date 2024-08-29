Taskify - Your Dynamic To-Do App
Taskify is a single-page application (SPA) built with React, Framer Motion, and Redux to manage your daily tasks efficiently. Here's how the app works:

1.Adding Tasks:
The app features an input field at the top where users can type in their tasks. Once a task is entered, clicking the "Add" button stores the task in the global Redux store, which ensures that the application's state is managed efficiently and consistently.

2.Displaying Tasks:
All tasks are displayed dynamically below the input field as a list of cards. Each card represents an individual task. These cards are enhanced with animations using Framer Motion, providing a smooth and visually appealing user experience when tasks are added, updated, or deleted.

3.Filtering Tasks:
Taskify offers three filter categories — All, Active, and Completed — which allow users to view tasks based on their status:
<br>
:- All: Displays all tasks, regardless of their status.<br>
:- Active: Shows only the tasks that are yet to be completed.<br>
:- Completed: Lists the tasks that have been marked as done.<br>
Clicking on any of these filters updates the view accordingly, without needing to reload the page, keeping the app fast and responsive.

4. CRUD Operations:
Each task card comes with full CRUD (Create, Read, Update, Delete) capabilities:

:- Create: Add new tasks using the input field.<br>
:- Read: View tasks based on the selected filter.<br>
:- Update: Modify any task directly from its card.<br>
:- Delete: Remove tasks using a delete button on each card.<br>

5.State Management with Redux:
The app leverages Redux to handle the application's state globally. This ensures that any changes, such as adding or deleting tasks, are instantly reflected across all relevant components without unnecessary re-renders or loss of state.

Live Demo :- https://huemn-assignment-two.vercel.app/

