# Kanban Board

A modern, highly interactive Kanban Board built with [Next.js](https://nextjs.org/), [React](https://reactjs.org/), and [Tailwind CSS](https://tailwindcss.com/). It provides a rich set of features for task management, including drag-and-drop reordering, rich text editing, tagging, and activity tracking.

## ✨ Features

- **Drag-and-Drop Interface:** Smooth and intuitive drag-and-drop for cards and columns powered by `@dnd-kit`.
- **Local Data Persistence:** Automatically saves your board state, columns, and cards to your browser's local storage so you never lose your work.
- **Rich Text Markdown Editing:** Write beautiful task descriptions with full Markdown support, including lists, code blocks, and formatting using `react-markdown`.
- **Multi-Tag System:** Categorize and color-code your tasks with multiple flexible tags per card.
- **Due Dates & Deadlines:** Set due dates for tasks with an integrated date picker and visual warnings for upcoming (yellow) and overdue (red) deadlines.
- **Advanced Search & Filtering:** Instantly filter your board by searching for text in titles or descriptions, or by filtering by priority and specific color tags.
- **Board Activity Log:** Automatically tracks and timestamps all board mutations (card creation, deletion, moving, and editing) in a sleek slide-out sidebar.
- **Dark Mode UX:** Designed with a premium, accessible dark theme featuring glassmorphism elements, custom animations, and responsive layouts.

## 🚀 Tech Stack

- **Framework:** [Next.js 14+] (App Router)
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Drag & Drop:** `@dnd-kit/core`, `@dnd-kit/sortable`
- **Markdown Rendering:** `react-markdown`, `remark-gfm`
- **Icons:** Inline SVG assets

## 📦 Getting Started

### Prerequisites

Ensure you have Node.js and npm (or yarn/pnpm) installed.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/bimashazaman/Kanban-Board.git
   cd Kanban-Board
   ```

2. Navigate to the frontend application directory:
   ```bash
   cd frontend
   ```

3. Install all dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🛣️ Roadmap

The frontend application provides a robust, single-user experience using local storage. Planned future enhancements include:
- Backend Database Integration (PostgreSQL/Supabase)
- User Authentication (NextAuth.js)
- Real-Time Multiplayer Syncing (WebSockets)

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
