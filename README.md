# <img src="public/favicon.ico" width="28" alt="Skill Barter"> Skill Barter: P2P Education Exchange

## 📝 Description
Skill Barter is a modern peer-to-peer platform where users can exchange skills and knowledge with each other without monetary transactions. In today's digital world, many people possess valuable skills they could teach others, while simultaneously wanting to learn new abilities. Traditional learning platforms are often one-directional and expensive, creating barriers to education. Skill Barter solves this problem by connecting people directly with each other in a barter economy of knowledge exchange, democratizing education and creating a collaborative learning ecosystem.

## 💡 Proposed System
Skill Barter will operate as a full-stack web application featuring:

- **User-centric Profile System**: Users create detailed profiles highlighting both the skills they can teach and those they wish to learn, with proficiency levels and availability preferences.
- **Smart Matching Algorithm**: The platform will automatically suggest potential matches based on complementary skill sets (where User A wants to learn what User B can teach and vice versa).
- **Real-time Communication**: Integrated messaging system allows users to discuss potential skill exchanges, coordinate schedules, and build community.
- **Session Management**: Tools for scheduling, tracking, and documenting skill exchange sessions.
- **Trust & Reputation System**: After exchanges, users rate each other, building a community based on trust and quality.
- **No Monetary Transactions**: The platform strictly facilitates skill-for-skill exchanges, removing financial barriers to education.

All interactions update in real-time, creating a dynamic platform that responds instantly to user actions and facilitates quick connections between learners and teachers.

## 🔍 Existing Systems and Drawbacks
Current solutions for skill development have significant limitations:

- **Traditional Education Platforms** (Coursera, Udemy): 
  - Primarily one-directional (expert to student)
  - Often require monetary payment
  - Lack personalization and direct interaction
  - No recognition of students' own teachable skills

- **Tutoring Services**:
  - Typically very expensive
  - Limited by geographical constraints
  - Operate on financial rather than skill exchange models

- **Community Forums/Social Media**:
  - Lack structured skill exchange frameworks
  - No verification of expertise or quality assurance
  - Limited tools for session coordination and follow-up

- **Existing Barter Apps**:
  - Focus primarily on goods rather than skills
  - Lack educational focus and specialized tools
  - Often have poor UX for knowledge exchange

Skill Barter addresses these gaps by creating a specialized platform explicitly designed for peer-to-peer skill exchange, with tools tailored for teaching and learning interactions, a reputation system to ensure quality, and a true barter economy that recognizes each user as both teacher and student.

## ✨ Features

- **🔐 User Authentication** - Secure signup and login
- **👤 Profile Management** - Customize your learning and teaching profile
- **🧠 Skill Management** - Add, edit, and track your skills and learning goals
- **🤝 Skill Barter System** - Match with users who can teach what you want to learn
- **💬 Real-time Communication** - Chat with connections and coordinate sessions
- **⭐ Rating & Feedback** - Build reputation through a robust rating system 
- **🎨 Dark Mode UI** - Beautiful, accessible interface with smooth animations

## 🛠️ Tech Stack

### Frontend
- **React + Vite** - Modern UI library with fast build tooling
- **TypeScript** - Type-safe JavaScript
- **TailwindCSS** - Utility-first CSS framework
- **Framer Motion** - Animation library for slick transitions
- **React Icons** - Beautiful icon library
- **React Router DOM** - Client-side routing

### Backend
- **Firebase Authentication** - User management and auth
- **Firebase Firestore** - NoSQL cloud database
- **Firebase Storage** - File storage
- **Socket.io** - Real-time bidirectional event-based communication

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- Firebase account

### Installation

1. **Clone the repository**
```bash
https://github.com/Vipulgupta23/Innov8ors_AMUHACKS4.0.git
cd p2p-education-barter
```

2. **Install dependencies**
```bash
npm install
```

3. **Environment Setup**
Create a `.env` file in the root directory and add your Firebase configuration:
```env
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

4. **Start the development server**
```bash
npm run dev
```

## 📂 Project Structure

```
src/
├── components/     # Reusable UI components
├── pages/          # Page components
├── services/       # Firebase and other services
├── hooks/          # Custom React hooks
├── context/        # React context providers
├── types/          # TypeScript type definitions
├── lib/            # Utility libraries
└── utils/          # Helper functions
```

## 📋 Features in Detail

### User Authentication
- Email and password authentication with Firebase
- Secure session management
- Profile creation with customizable skills and interests

### Skill Management
- Add skills with categories and proficiency levels
- Tag skills for better discoverability
- Manage desired skills to learn
- Set skill preferences and goals

### Skill Barter System
- Browse and search for skills with advanced filtering
- Send connection requests with personalized messages
- Initiate skill exchange sessions with scheduling
- Real-time updates for requests and session status

### Real-time Communication
- Instant messaging with connections
- Session coordination and planning
- Notification system for important events

### Rating System
- Rate skill exchange sessions on multiple criteria
- Provide detailed feedback for improvement
- View aggregate ratings to build reputation

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [React](https://reactjs.org/)
- [Firebase](https://firebase.google.com/)
- [TailwindCSS](https://tailwindcss.com/)
- [Framer Motion](https://www.framer.com/motion/)
- [Socket.io](https://socket.io/)

---

<p align="center">
  <img src="public/favicon.ico" width="40" alt="Skill Barter">
  <br>
  <i>Connect. Learn. Teach.</i>
</p>
