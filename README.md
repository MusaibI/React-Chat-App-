# React Chat Application

This project is a **React-based chat application** built with **React Hooks** and **Redux** for state management. The goal of this project is to replicate a messaging app similar to the one shown in the mockup provided. It features a conversation list, a chat window to display messages, and a system to start new conversations with contacts loaded from dummy data.

## Features

### 1. **Conversations List (Left Sidebar)**
   - Displays all active conversations.
   - Shows contact name and the most recent message in each conversation.
   - Allows searching for conversations by contact name.
   - Includes a "New Conversation" button to start a chat with any contact from a predefined list of dummy contacts.

### 2. **Chat Window (Right Side)**
   - Displays messages for the selected conversation.
   - Allows the user to send new messages.
   - Shows the sender’s name, message content, and timestamp for each message.
   - Supports real-time updates for message sending within the selected conversation.

### 3. **Create New Conversation**
   - Upon clicking the "New Conversation" button, a modal opens with a list of available contacts (loaded from dummy data).
   - The user can start a new conversation if one doesn't already exist, or jump to the existing chat if it does.

### 4. **Search Functionality**
   - The search bar allows users to filter conversations by contact name in real-time.

### 5. **State Management with Redux**
   - The app uses Redux to handle state management across components.
   - Redux is utilized for managing the list of conversations and the currently active conversation.

### 6. **Persistence with LocalStorage (Bonus Feature)**
   - Redux data (conversations and messages) is persisted across page reloads using `localStorage`. This ensures that the conversations remain intact even if the user refreshes the browser.

### 7. **Error Handling and Notifications**
   - Error handling for message sending and conversation creation.
   - Alerts and notifications are triggered to provide feedback to the user.

## Tech Stack
- **React**: Frontend library for building the UI.
- **Redux**: State management library for managing conversation data.
- **React-Router**: For navigation between the conversations and the chat window.
- **JSON**: Dummy data for simulating users, conversations, and messages.

## How to Run Locally

### Prerequisites
- Node.js and npm installed.

### Steps:
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/react-chat-app.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd react-chat-app
   ```
3. **Install dependencies:**
   ```bash
   npm install
   ```
4. **Start the development server:**
   ```bash
   npm start
   ```
   The app will be running on `http://localhost:3000`.

## Future Enhancements
- Integrating real-time messaging using WebSockets.
- Adding authentication for multiple users.
- Improving the UI/UX with custom themes.
- Implementing a backend for persistent storage of conversations.

## Contributions
Feel free to fork the repository, make improvements, and submit pull requests!
