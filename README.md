# cyb
Engaging web-based game teaching cyber security awareness to everyday users, using HTML, CSS and JavaScript, together with LocalStorage API to save quiz scores, points and user progress in the browser. Share. Learn. Play.

Project Manager: Matthew Friel

Designers: Abdulla al Bassam, Josh Healy

Cyber Consultant: Thomas Armstrong 

Developers: Sean Zamora, Shabbir Ahmed

The concept was straightforward: transform the often tedious fundamentals of introductory cybersecurity, like key terminology, common attacks and defensive practices, into an engaging, game-like experience rather than a traditional textbook. Users create an account, explore bite-sized learning cards, and participate in interactive game rounds, earning XP and progressing through levels as they answer questions correctly.

## Repo Content

- `index.html`: single-page UI: login, sign-up, home, quick facts, and the game views, all swapped through CSS classes
  
- `app.js`: the client-side logic: localStorage-backed accounts, session handling, view switching, the XP and level system, and the game state machine
  
- `styles.css`: the visual language, including the retro pixel-font logo and the auth and home layouts
No backend, no build step. Everything runs in the browser using localStorage for accounts and progress

## How to run Cyb

Clone the repo and open index.html in a browser:

```bash
git clone https://github.com/sean-p-zamora/cyb.git
cd cyb
open index.html
```
Can be served locally for clean paths in DevTools:

```bash
python3 -m http.server 8000
```

Then visit - http://localhost:8000

## Status

This is a coursework artefact. It is not maintained and is not intended as a production learning platform; it is a teaching demo and a record of the group's work.
