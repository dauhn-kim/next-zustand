# NextJS 14 Task Tracker with Zustand State Management

This project is inspired by the robust state management capabilities of Zustand
and seeks to implement a dynamic task tracker (Kanban board) within the NextJS
14 framework. By leveraging Zustand, we manage global state efficiently,
enabling features like drag-and-drop task management and persistent state
storage through local storage.

## Features

- **Task Management**: Create, view, and delete tasks within a Kanban-style
  board.
- **Drag & Drop**: Seamlessly change a task's status by dragging it across
  different columns.
- **Persistent State**: Utilize Zustand's middleware to save and load tasks from
  local storage, ensuring data persistence across sessions.
- **Hydration Strategy**: Solve NextJS-specific hydration issues by delaying
  state rehydration until the client-side, ensuring seamless server-side
  rendering and client-side hydration.

## Getting Started

1. **Clone the repository**

```bash
git clone https://github.com/YourGitHub/nextjs-zustand.git
cd nextjs-zustand
```

2. **Install dependencies**

```bash
npm install
# or
yarn
```

3. **Run the development server**

```bash
npm run dev
# or
yarn dev
```

Navigate to `http://localhost:3000` to see your task tracker in action.

## Usage

- **Add a Task**: Click the 'Add Task' button, enter the task details, and
  submit.
- **Edit Task State**: Click and drag tasks across columns to change their
  status.
- **Delete a Task**: Click the 'Delete' button on any task to remove it from the
  board.

## Contributing

Contributions are welcome! If you have ideas for improvements or encounter any
issues, please open an issue or submit a pull request.

## Acknowledgments

Special thanks to Hamed Bahram for the educational content and Niklas Ziermann
(@NiklasZiermann) at freeCodeCamp for the initial inspiration. This project
builds upon their foundational work to explore state management in NextJS with
Zustand.
