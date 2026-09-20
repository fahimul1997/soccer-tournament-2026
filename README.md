# Soccer Tournament 2026 Live Website

Public tournament website with Firebase live data and Firebase email/password admin login.

## Tournament rules
- 10 teams, Group A and Group B, 5 teams each
- Group stage: 20 minutes straight, no halftime
- Knockouts: 15 minutes per half
- Top 2 from each group advance to semifinals
- SF1: Group A #1 vs Group B #2
- SF2: Group B #1 vs Group A #2
- Win 3, draw 1, loss 0
- Tiebreakers: points, goal difference, goals scored
- 2 accumulated yellow cards = 1-game suspension
- 1 red card = 1-game suspension
- Final is exempt from suspension serving
- Rosters lock when the admin uses Lock Group Stage

## Setup
1. Create a Firebase project.
2. Add a Web App and copy its config into firebase-config.js.
3. Enable Authentication > Email/Password and create the admin account.
4. Create Realtime Database and apply firebase-rules.json.
5. Enable GitHub Pages for the main branch/root folder.
6. Open the GitHub Pages URL. Visitors use the public tabs; the organizer uses Admin Login.

The Firebase config file is intentionally a placeholder until your Firebase project is created.