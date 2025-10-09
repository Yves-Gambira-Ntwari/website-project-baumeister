# website-project-baumeister

## website-Baumeister
The purpose is to learn and to know how to collaborate with others

### 🧭 Project Setup and Git Remote Configuration

### The structure of our project

```bash 
WEBSITE-BAUMEISTER/ Frontend
│
├── node_modules/
├── src/
│ └── components/
│ └── Footer.js
|
├── assets/
│ └── images/
| |__css/style.css
│
├── LICENSE
├── package-lock.json
├── package.json
├── .gitignore
|__index.html
└── README.md
```
### ⚠️Run these commands to get on truck

```bash
npm init -y
npm install -D vite @tailwindcss/vite
```

### ⚠️Update package.json

- Replace this script with your script in

package.json

"script":{
"dev":"vite",
"build": "vite build",
"preview": "vite preview"
}

### How to run dev

```bash
npm run dev
```

### Commit messages

##### Common commit types for comparison

- Type Meaning
- feat: New feature added
- fix: A bug fix
- docs: Documentation change
- style: Code style changes (formatting, spaces, semicolons)
- refactor: Code changes that don’t change \* behavior but improve structure
- test: Adding or modifying tests
- chore: Maintenance tasks, builds, or dependency updates
