# Website Accessibility Audit & Project Architecture

## Project Overview
This project focuses on auditing a public-facing website for accessibility and establishing a maintainable monorepo-style project structure.

## Website Audited
- Website: W3C
- URL: https://www.w3.org/
- Tool: Google Chrome Lighthouse
- Accessibility Score: 96/100
- Keyboard Navigation: Passed manual testing

## Project Architecture

```text
website-accessibility-audit/
│
├── client/
│   └── README.md
│
├── server/
│   └── README.md
│
├── docs/
│   ├── audit-report.md
│   └── screenshots/
│
├── test/
│   └── README.md
│
└── README.md
```

## Architecture Explanation

### Client
Responsible for frontend development, user interface, responsive design and accessibility.

### Server
Responsible for backend logic, API handling and data processing.

### Docs
Contains audit reports, architecture documentation and screenshots.

### Test
Contains testing documentation and quality assurance activities.

## Local Setup

1. Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

2. Open the project directory:

```bash
cd website-accessibility-audit
```

3. Explore the client, server, docs and test directories.

Note: This repository currently provides a project skeleton. Frontend and backend applications can be added in future development.

## First Vertical Feature Slice

The first planned feature is an accessible website audit dashboard.

- Client: Display audit results.
- Server: Provide audit result data through an API.
- Docs: Document the audit process.
- Test: Verify accessibility and functionality.

## Conclusion
This project establishes an accessible, organized and maintainable foundation for future full-stack development.
