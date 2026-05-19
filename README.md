# Workspace Inteligente

A lightweight task management web application built with vanilla JavaScript, focused on strategic data persistence using `localStorage` and `sessionStorage`.

## Overview

This project was developed as part of a JavaScript challenge centered on DOM manipulation and browser storage management. The application allows users to manage tasks dynamically while deciding which information should persist permanently and which should remain temporary during the current session.

## Features

- Add new tasks
- Mark tasks as completed
- Delete tasks
- Dynamic task filtering:
  - All tasks
  - Pending tasks
  - Completed tasks
- Real-time DOM updates without page reloads
- Persistent data management using Web Storage APIs

## Storage Strategy

### localStorage

Used for information that must persist even after the browser is closed.

Stored data:

- Task list
- Task completion status

Example structure:

```json
[
  {
    "id": 1,
    "text": "Finish JavaScript challenge",
    "completed": false
  }
]
