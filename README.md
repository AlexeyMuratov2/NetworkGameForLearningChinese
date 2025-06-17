# Hanyu Duel

**Hanyu Duel** is a multiplayer quiz game (2–6 players) focused on Chinese language knowledge. Players join a session, wait until all are ready, and then compete in answering questions in real-time.

The project is split into two parts:  
- `server/` — handles game sessions, logic, and communication via TCP sockets  
- `client/` — a Java Swing GUI that connects to the server and allows users to play

Built with Java 17, Maven, and plain sockets (no Spring).  
More features like a database and score tracking will be added later.
