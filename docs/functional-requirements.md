# Functional Requirements: TODO App

This document lists the core functional requirements for the TODO application.

## Task Management

- **Create task**: The user can create a new task with a title/description.
- **Edit task**: The user can edit an existing task's details (e.g., title, description, due date).
- **Delete task**: The user can delete a task.
- **Complete task**: The user can mark a task as complete or incomplete.

## Due Dates

- The user can add a due date to a task when creating or editing it.
- The due date is optional; tasks without a due date are still valid.
- Tasks with an overdue due date should be visually distinguishable from other tasks.

## Task Ordering

- Tasks are sorted in a specific order:
  1. Incomplete tasks are shown before completed tasks.
  2. Within each group, tasks are sorted by due date (earliest due date first).
  3. Tasks without a due date are sorted after tasks with a due date, within their group.

## Persistence

- Tasks persist across page reloads/sessions.
