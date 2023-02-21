# Completum

The purpose of this markdown file is to walkthrough some of the features provided by my to-do list application: [Completum](https://completum.fly.dev).

## Adaptive and Responsive User Interface

![GIF demonstrating the adaptive and responsive design of the web application](/gifs/AdaptiveResponsiveDisplay.gif)

## Login

Upon logging in, you are assigned a unique JSON web token that allows you to send API requests. If you have not logged out and decided to revisit the login page, you are greeted with a welcome message.

![GIF showing a user revisiting the login page](/gifs/DesktopRememberLogin.gif)

## Tasks

You provide the task title in the task creation text field to create a task. Tasks are categorised as **General** when creating a task whilst you are viewing your tasks in the **My Day**, **All Tasks**, or **This Week** view. You can change the default assigned category by clicking on the task and editing its category field.

Checking a task as completed causes the priority colour to transform into a bin icon. Clicking the bin icon deletes a task. It is possible to mass-delete completed tasks in the options.

### View Tasks

![GIF of user viewing various tasks](/gifs/MobileViewTasks.gif)

### Create, Edit and Delete Tasks

![GIF showing the creating, deleting and editing of a task](/gifs/MobileCreateEditDeleteTask.gif)

### Mass Delete Tasks

![GIF showing mass removal of tasks](/gifs/DesktopMassDelete.gif)

## Categories

### Create and Delete Categories

![GIF showing the creation and deletion of a category](/gifs/MobileCreateDeleteCategory.gif)

All tasks associated with a category are removed when that category is deleted. By design, it is impossible to delete the **General** category.
