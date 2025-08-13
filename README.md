# exam-prep-hub

A web-based exam preparation platform for practicing **Literature**, **Math**, and **Art aptitude** tests.  
It provides an interactive experience with:

- **Real-time commenting and highlighting** (similar to MS Word)
- **Timed test sessions** with pause/resume support
- **Auto-scoring** for multiple-choice questions
- **Drawing tools** for art practice

---

## 🚀 Tech Stack

### API
- **Node.js** + **Express.js**
- **TypeScript**
- **MongoDB**
- ESLint + Prettier for code quality

### Client
- **React** + **Vite**
- **TypeScript**
- **Tailwind CSS**
- ESLint + Prettier for code quality

### Development
- **pnpm** (workspace monorepo)
- **concurrently** for running API & client together

---

## 📂 Folder Structure
exam-prep-hub/
│
├── api/ # Backend (Express + TS + MongoDB)
├── client/ # Frontend (React + Vite + Tailwind)
├── package.json # Workspace root config
├── pnpm-workspace.yaml
├── .gitignore
└── README.md


## 🛠 Development Setup

1. **Clone the repo**
```bash
git clone https://github.com/htnhan-dev/exam-prep-hub.git
cd exam-prep-hub

2. **Install dependencies**
```bash
pnpm install


3. **Run API & Client together**
```bash
pnpm dev


4. **Run individually**
```bash
pnpm --filter api dev
pnpm --filter client dev
