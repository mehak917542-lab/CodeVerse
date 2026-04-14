A full-stack social network platform for developers to connect, share posts, and showcase their GitHub profiles.

Built using the MERN Stack (MongoDB, Express, React, Node.js)
## ✨ Features

- 🔐 JWT-based user authentication
- 👤 Developer profile creation & editing
- 📝 Post creation, likes, comments
- 🔍 View other developer profiles
- 🐙 GitHub repository integration via GitHub API
- 🔄 Responsive design with clean UI
- 🛡️ Route protection for private pages

---

## 🧱 Tech Stack

| Frontend         | Backend          | Database      | Auth           |
|------------------|------------------|---------------|----------------|
| React, Redux     | Node.js, Express | MongoDB Atlas | JWT, bcrypt.js |

Additional tools:
- Axios
- Normalize-URL
- Redux DevTools
- GitHub Personal Access Token for API

---
### 1. Clone the repository

```bash
git clone https://github.com/Sonali23-student/CodeNetwork.git
cd CodeNetwork
server:
npm install
client:
cd client
npm install
set environment:
{
  "mongoURI": "<your_mongoDB_URI>",
  "jwtSecret": "<your_jwt_secret>",
  "githubToken": "<your_github_access_token>"
}
Run the App:
npm run dev
