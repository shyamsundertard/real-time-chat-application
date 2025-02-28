# Real-Time Chat Application

This repository serves as the main project hub for a full-stack real-time chat application built with Nextjs, Strapi, Node.js, and Socket.IO.

## Website: https://quick-ping.vercel.app/QuickPing
### Dummy Account Credentials:
   - 📧 Email: user@quickping.com
   - 🔑 Password: user4qp

## Project Structure

The application is divided into two main components:
- [Frontend Repository](https://github.com/shyamsundertard/chat-frontend)
- [Backend Repository](https://github.com/shyamsundertard/chat-backend)

## Backend Features

### Socket.IO Integration
- Real-time bidirectional communication using Socket.IO
- CORS configuration for secure cross-origin requests
- Event-based message handling
- Automatic reconnection management

### User Management
- Username retrieval functionality
- User authentication integration with Strapi's users-permissions plugin
- User verification before chat operations

### Chat Session Management
- Create new chat sessions with custom titles
- List all chat sessions for a specific user
- Sort sessions by most recently updated
- Automatic session joining upon creation
- Session selection capability

### Message Handling
- Real-time message exchange between user and system
- Timestamp tracking for all messages
- Message history retrieval for each chat session
- Automatic system response to user messages (echo functionality)
- Welcome messages for new chat sessions

### Room-Based Communication
- Socket room functionality for organizing conversations
- Join specific chat rooms based on session ID
- Isolated message broadcasting within rooms
- Session-specific message delivery

### Error Handling
- Comprehensive error checking for missing parameters
- Graceful error handling with detailed logging
- Socket error event monitoring

### Data Persistence
- Integration with Strapi entity service
- Storage of user information, chat sessions, and messages
- Automatic timestamp updates for session activity
- Sorting and filtering capabilities for data retrieval

## Frontend Features

### User Interface
- Intuitive chat interface
- Message input area with send button
- Real-time message display
- Message timestamps
- Session switching capability
- User authentication forms (login, signup)

### WebSocket Integration
- Real-time communication with backend server
- Automatic reconnection handling

### Responsive Design
- Fully responsive layout for all device sizes
- Mobile-first approach
- Adaptive UI elements for different screen sizes
- Touch-friendly interface for mobile devices
- Consistent experience across desktop, tablet, and mobile views

### User Authentication
- Login form with validation
- Registration form with validation
- Secure token storage
- Authentication state management
- Protected routes for authenticated users

## Technologies Used
- **Frontend**: Nextjs, Socket.IO Client
- **Backend**: Strapi, Node.js, Socket.IO
- **Database**: Postgres (via Railway)
- **Authentication**: JWT (via Strapi)
