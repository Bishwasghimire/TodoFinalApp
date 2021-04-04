# Todo App
This is a simple todo application. It has the features to add, update and delete task.

## App Demo
Demo of the application.

![](app/src/main/res/drawable/app_use.gif)

## Splash Screen
On clicking the app, a splash screen will appear at first, then the main activity appears.

![](app/src/main/res/drawable/open_app.gif)

## Task Add
Clicking on the + button at the right bottom of the screen opens a screen from where users can add task. The task has properties like task name, due date and priority.

![](app/src/main/res/drawable/add_task.gif)

## Task Update
Clicking on the task in the screen takes user to the activity from where task can be updated by clicking update button.

![](app/src/main/res/drawable/update_task.gif)

## Task Delete
Task can be deleted either by swiping left/right or clicking on the task and clicking on delete button. On click, a dialog box appears to confirm users choice. Clicking on delete will delete the task.

<table>
<tr>
<td>By clicking on the task</td>
<td>By swiping right or left</td>
</tr>
<tr>
<td><img src="app/src/main/res/drawable/delete_task.gif"></td>
<td><img src="app/src/main/res/drawable/on_swipe_delete.gif"></td>
</tr>
</table>

## Delete All Task
All tasks can be deleted at once by clicking on the menu option and choosing delete all task. After that, a dialog box appears to confirm users choice. Clicking on delete will delete all tasks.

![](app/src/main/res/drawable/delete_all_task.gif)

## Data saved on rotation
onSaveInstanceState is used to save important data before the activity is destroyed. On activity resume, we can restore those data.

![](app/src/main/res/drawable/save_instance.gif)
