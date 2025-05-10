# Kanban Task Board

This **Kanban Task Board** built with **React**, **TypeScript**, **Zustand**, and **drag-and-drop** capabilities. This board allows users to manage multiple projects, organize tasks across three workflow stages (To Do, In Progress, Done), and persist all data using `localStorage`.

## Live Demo

🔗 [View Live Project](To be updated)

## Features

### Must-Haves (accomplished)

- **Project Sidebar**
  - Create, rename, and delete projects
  - Select and switch between projects

- **Board Layout**
  - Three fixed columns: _To Do_, _In Progress_, _Done_
  - Fully responsive layout

- **Task Cards**
  - Title (required)
  - Optional description
  - Created date display
  - Edit & delete actions

- **Task Modals**
  - Modal/form interface for adding/editing tasks
  - Title validation
  - Choose initial column during task creation

- **Drag and Drop**
  - Move tasks across columns using `@dnd-kit/core` or `react-beautiful-dnd`

- **Persistence**
  - All data (projects + tasks) saved to `localStorage`

### Optional Bonus Features

- [ ] Light/Dark mode toggle
- [ ] Due date field with overdue status indicator

## Tech Stack

- **React** + **TypeScript**
- **Zustand** – for global state management
- **TailwindCSS** – for styling
- **@dnd-kit/core** – drag-and-drop library
- **localStorage** – for persistence
