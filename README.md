# APIPlayground

A full-stack API playground featuring an Express backend with an interactive frontend for testing RESTful endpoints. Perfect for demonstrating full-stack development skills.

**🌐 Live Demo:** [View on Vercel](https://your-vercel-url.vercel.app)  
**📦 Repository:** [GitHub](https://github.com/awonuga123/beginner-backend)

---

## About This Project

APIPlayground is a complete full-stack application that showcases:
- **Backend Development** with Node.js and Express
- **Frontend Engineering** with vanilla JavaScript, HTML5, and CSS3
- **API Design** with RESTful principles
- **Deployment** on modern cloud platforms (Vercel)
- **Git Workflow** with version control best practices

## Tech Stack

**Backend:**
- Node.js runtime
- Express.js framework
- CORS middleware for cross-origin requests
- RESTful API design

**Frontend:**
- HTML5 semantic markup
- CSS3 with modern styling
- Vanilla JavaScript (ES6+)
- Fetch API for HTTP requests

**DevOps & Deployment:**
- Git version control
- GitHub repository
- Vercel serverless deployment
- Environment-based configuration

## Features

✨ **Interactive API Tester** — Beautiful UI with real-time response display  
🚀 **Production-Ready Backend** — Multiple endpoints with proper error handling  
📱 **Responsive Design** — Works on desktop and mobile devices  
🔌 **CORS Enabled** — Ready for frontend integration from any domain  
☁️ **Serverless Deployment** — Auto-scaling on Vercel  
🎨 **Modern Styling** — Professional black and red color scheme  

## API Endpoints

| Method | Route | Description |
|--------|-------|-------------|
| GET | `/` | Welcome message |
| GET | `/api/hello` | Returns a JSON greeting |
| POST | `/api/echo` | Echoes back the request body |

## Quick Start

### Local Development

```powershell
# Clone the repository
git clone https://github.com/awonuga123/beginner-backend.git
cd beginner-backend

# Install dependencies
npm install

# Start development server
npm start
# or with auto-reload:
npm run dev
```

Visit `http://localhost:3000` to see the interactive frontend.

### Testing Endpoints

**Welcome:**
```powershell
curl http://localhost:3000/
```

**Hello:**
```powershell
curl http://localhost:3000/api/hello
```

**Echo (sends data back):**
```powershell
curl -X POST http://localhost:3000/api/echo `
  -H "Content-Type: application/json" `
  -d '{ "name": "Jane" }'
```

## Project Structure

```
api-playground/
├── index.js              # Main Express server
├── package.json          # Dependencies & scripts
├── vercel.json           # Vercel deployment config
├── .gitignore            # Git ignore rules
├── README.md             # Documentation
├── public/               # Frontend files
│   ├── index.html        # Interactive UI
│   ├── style.css         # Responsive styling
│   └── script.js         # API client logic
└── routes/               # API route modules
    └── echo.js           # Echo endpoint handler
```

## Key Learnings Demonstrated

### Backend
- Express.js server setup and configuration
- RESTful API design patterns
- CORS and middleware handling
- Environment variable configuration
- Static file serving

### Frontend
- Fetch API for making HTTP requests
- Dynamic DOM manipulation
- Error handling and loading states
- Responsive UI design
- Clean, maintainable JavaScript code

### DevOps
- Git workflow and commits
- GitHub repository management
- Continuous deployment on Vercel
- Environment configuration for different stages

## Future Enhancements

- [ ] Add database integration (MongoDB/PostgreSQL)
- [ ] Implement user authentication (JWT)
- [ ] Build admin dashboard
- [ ] Add rate limiting
- [ ] Write unit and integration tests
- [ ] Add API documentation (Swagger/OpenAPI)

## Author

Built as a portfolio project to demonstrate full-stack web development skills.

---

**Want to hire me?** Check out my [portfolio](your-portfolio-url) for more projects!
