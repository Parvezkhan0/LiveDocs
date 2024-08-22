

# Live Docs

Live Docs is a real-time collaborative document editor designed to enhance productivity and teamwork. It allows multiple users to work simultaneously on documents, with instant updates, making it an ideal tool for remote collaboration, brainstorming sessions, and document management.

## 🚀 Features

- **Real-Time Collaboration**: Multiple users can edit documents at the same time, with changes visible in real-time.
- **User Authentication**: Secure login and session management using NextAuth with GitHub authentication.
- **Document Management**: Create, edit, delete, and share documents with ease. Manage permissions for collaborators.
- **Inline and General Comments**: Add, reply, and manage comments directly within documents, supporting threaded discussions.
- **Active Collaborators**: See who's editing the document in real-time, with presence indicators.
- **Notifications**: Get notified when a document is shared, when new comments are added, or when collaborators make changes.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## 🛠 Tech Stack

- **Next.js**: Framework for the user interface.
- **TypeScript**: Strongly typed JavaScript for better maintainability.
- **Liveblocks**: Handles real-time collaboration and synchronization.
- **Lexical Editor**: A rich text editor built for extensibility.
- **ShadCN**: Provides pre-styled UI components.
- **Tailwind CSS**: Utility-first CSS framework for fast styling.

## 📦 Quick Start

### Prerequisites

Ensure you have the following installed:
- Git
- Node.js
- npm

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Parvezkhan0/LiveDocs.git
   cd LiveDocs
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the project root.
   - Add your Clerk and Liveblocks API keys:
     ```bash
     NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_key
     CLERK_SECRET_KEY=your_clerk_secret
     NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=your_liveblocks_key
     LIVEBLOCKS_SECRET_KEY=your_liveblocks_secret
     ```

4. Run the project:
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) to view the app.

## 🗂 Project Structure

- **`/app`**: Main application logic.
- **`/components`**: Reusable UI components.
- **`/lib`**: Utility functions and configurations.
- **`/public`**: Public assets like images.
- **`/styles`**: Global and component-specific styles.
- **`/types`**: TypeScript types.


