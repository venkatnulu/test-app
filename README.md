# quiz-cli

An interactive command-line quiz game for learning JavaScript.

## Table of Contents

- [Project Description](#project-description)
- [Technology Stack](#technology-stack)
- [Repository Structure](#repository-structure)
- [Installation](#installation)
- [Configuration](#configuration)
- [Build Instructions](#build-instructions)
- [Run Instructions](#run-instructions)
- [Key Features](#key-features)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Project Description

`quiz-cli` is a CLI-only quiz application that runs in Node.js and lets users practice JavaScript through an interactive question-and-answer flow.

It appears to be designed for:

- learners who want a lightweight JavaScript practice tool
- users who prefer terminal-based applications
- quick self-assessment through scoring and answer review

The repository evidence indicates the app supports:

- category selection
- question selection
- scoring
- progress display
- replay loop
- answer review

## Technology Stack

| Layer | Details |
|---|---|
| Runtime | Node.js >= 18 |
| Module system | ES Modules |
| Language | JavaScript |
| Dependencies | No external npm dependencies |
| Entry point | `index.js` |
| Quiz data | `data/questions.json` |
| CLI | Terminal-based application |
| API | None (no REST/GraphQL/API) |

## Repository Structure

Based on the available repository evidence:

```text
quiz-cli/
├── index.js
├── data/
│   └── questions.json
├── src/
│   ├── quiz.js
│   ├── input.js
│   └── colors.js
└── package.json
```

> Note: `package.json` is implied by the provided `npm start` and `npm test` commands, but no file contents were supplied.

## Installation

### Prerequisites

- Node.js `18` or newer

### Setup

1. Clone the repository.
2. Change into the project directory.
3. Ensure Node.js 18+ is installed.
4. No external npm dependencies are required.

Example:

```bash
git clone https://github.com/venkatnulu/test-app.git
cd test-app
```

## Configuration

The repository evidence does not mention environment variables or external configuration files.

What is known:

- Quiz content is stored in `data/questions.json`
- The app uses ES Modules
- No secrets or credentials are required

If you want to change quiz content, update `data/questions.json`.

## Build Instructions

No build step is specified in the repository evidence.

Since this is a Node.js CLI app with no external dependencies, it appears to run directly without a compile or bundle process.

## Run Instructions

You can start the quiz using either of the following commands:

```bash
npm start
```

or:

```bash
node index.js
```

## Key Features

- Category selection
- Question selection
- Score tracking
- Progress display
- Replay loop for repeated play sessions
- Answer review at the end of the quiz

## Testing

The repository evidence indicates the following test commands:

```bash
npm test
```

or:

```bash
node --test
```

No specific testing framework or coverage tooling was provided in the repository evidence.

## Contributing

No `CONTRIBUTING.md` file was found in the repository evidence.

If you want to contribute, a standard workflow would be:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run the test command
5. Open a pull request

## License

No license file was found in the repository evidence.

License information is **not specified in this repository**.
