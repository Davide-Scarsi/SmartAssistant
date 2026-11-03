# SmartAssistant

SmartAssistant is a Windows desktop app that makes Claude know your projects.
Point it at your project folders: it reads them, keeps up with every change and
commit, and gives that knowledge to Claude Desktop and Claude Code. When a ticket
comes in, you ask Claude and it already knows where to look.

## Your projects, always known

- Add a project by choosing its folder: no workspace or editor needed
- Reads the code, the structure and the git history ahead of time: classes, methods,
  the entity and field names your code uses (such as `vic_contratto`), header comments,
  entry points, README, and which files each commit touched
- Stays up to date by itself: a changed file or a new commit is picked up within seconds,
  and only what changed is read again
- Skips build output and packages (`bin`, `obj`, `node_modules`, …) and whatever git ignores
- Never touches your projects: everything it knows is kept in its own folder

## Claude, with the knowledge

- One click connects it to Claude Desktop and to Claude Code, with the state always
  visible — no need to know what MCP is
- Claude starts from the knowledge: it finds the right files, reads only those and answers
  with files and lines
- When a ticket is solved, Claude offers to save the answer; the next time a similar
  ticket comes in, it finds it right away
- Write notes for what the code does not say — what a module is for, who uses it,
  what not to touch — and Claude reads them every time
- "Prova la ricerca" (Try the search) shows what Claude would find for the words of a ticket
- Credentials stay out: key and certificate files and `.env` are never read, and
  passwords in connection strings are hidden before anything reaches Claude

## The map

- See your knowledge as a living network: each project with its code areas and most
  worked-on files, its history, saved answers and notes
- Answers and commits are wired to the files they cite or touched, and sparks run along
  the wires
- Updates live: a new commit or a saved answer appears and flashes while you watch
- Search the map, filter what you see, click any node to read what is known about it

## Install

Download `SmartAssistant_Setup.exe` from the [latest release](../../releases/latest) and run it.
Then:

1. **Progetti → Aggiungi cartella** (Projects → Add folder) for each project.
2. **Claude → Collega** (Connect) for Claude Desktop and/or Claude Code. Restart Claude Desktop
   after connecting it.
3. Ask Claude about your projects.

SmartAssistant updates itself from this page: when a new version is out, the app offers
it with one click.

The app is in Italian. Windows 10/11 only. Public releases only — the source code is private.
