# To-Do List API

## GET /tasks
- Description: Get all tasks
- Response: JSON array of tasks

## POST /tasks
- Description: Add a new task
- Request: { "name": "Task 1", "description": "Sample task" }
- Response: Created task object

## PUT /tasks/{id}
- Description: Update a task
- Request: { "name": "Updated", "description": "Updated description" }
- Response: Updated task object

## DELETE /tasks/{id}
- Description: Delete a task
- Response: 204 No Content
