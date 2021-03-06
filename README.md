## Goal

The Goal of this tech test is to test your knowledge with Ruby on Rails and implement a short Stimulus controller. This tech test will cover some Rails, ActiveRecord and Stimulus concepts. You can use Bootstrap and [Le Wagon UI Kit](https://uikit.lewagon.com).

## Challenge

- Create a to-do list Rails app and a Task model with a name, a description, a completed field and a deadline date.
- The app will only have one page: at the top, the form to add a new Task to your to-do list, and at the bottom the list.
- New tasks should be inserted without reloading the page, and should be sorted from the oldest to the newest deadline.
- Each task should have a checkbox or an icon to indicate whether the task has been completed.
- You can try using Stimulus and create a Stimulus controller to handle this. You can check the lecture `From design to code` from the bootcamp to get started.

## Bonus

- Sort tasks by not completed first, so when a task is marked as completed it should jump to the bottom of the list
- Add a section on your to-do list regrouping the tasks that have been missed (not completed and with a deadline in the past). You can try using a model scope.
- Without implementing them, which tests could you write to make sure your app is robust?

## Submission

- Make sure to edit the Readme file to add your instructions on how to run your app properly, install gems if needed and setup the database to have at least a few tasks from the seeds to display.
- Send back your repo to Anne 🤗
