# Demo Run CI/CD with Node.js

This is a demostration of CI/CD with Node.js

## Prerequisites
- Node.js
- NPM
- Git
- GitHub

---

## Structure

```
└── 📁demo-cicd-node
    └── 📁.github
        └── 📁workflows
            ├── ci.yml
    └── 📁.qodo
        └── 📁agents
        └── 📁workflows
    └── 📁test
        ├── sample.test.js
    ├── index.js
    ├── package.json
    └── README.md
```

---

## Installation

1. Clone the repository

```bash
git clone https://github.com/heliomarpm/ci-cd-node.git
```

2. Install dependencies

```bash
cd ci-cd-node
npm install
```

3. Run the tests

```bash
npm test
```

4. Create a new branch

```bash
git checkout -b feature/foo
```

5. Commit the changes

```bash
git add .
git commit -m "feat: add foo"
```