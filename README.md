# ABC Training School Copilot Extension

This repository demonstrates a Copilot extension for ABC Training School, specializing in coaching athletes, conducting tournaments, organizing sponsors, and celebrating award-winning alumni.

## Features
- **Copilot Chat Agent:** AI-powered assistant for school-related queries via `/copilot` endpoint.
- **Tournament Scheduler:** View upcoming tournaments and registration deadlines via `/tournaments` endpoint.
- **Coach Directory:** Browse profiles of experienced coaches via `/coaches` endpoint.
- **Knowledge Base:** Markdown files in `agent-knowledge` provide context for Copilot responses.

## Getting Started
1. Install dependencies:
   ```sh
   cd abc-training-school-extension-js
   npm install
   ```
2. Start the extension server:
   ```sh
   npm start
   ```
3. Access the homepage at [http://localhost:3000](http://localhost:3000) or your Codespace URL.

## Endpoints
- `/copilot` — Main chat endpoint for GitHub app integration.
- `/tournaments` — Lists upcoming tournaments (markdown).
- `/coaches` — Lists coach profiles (markdown).
- `/info` — Extension homepage.

## Sample Prompts
- "Show me the upcoming tournaments and registration deadlines."
- "List all coaches and their areas of expertise."
- "How can I register for the Summer Sports Fest 2025?"

## Folder Structure
- `abc-training-school-extension-js/`
  - `index.js` — Main Express server.
  - `agent-knowledge/` — Markdown files for agent context.
  - `info.html` — Homepage.
  - `package.json` — Project dependencies.

## License
MIT
