## csci3308-project
Software Development and Tools - Spring 2016 Term Project

##### Who:

- Christine Samson ([casamson](https://github.com/casamson))
- Nolan Cretney ([nokynokes](https://github.com/nokynokes))
- Evan Su ([hexacyanide](https://github.com/hexacyanide))
- Michael Xiao ([MDXiao](https://github.com/MDXiao))
- David Kleckner ([D-Kleck](https://github.com/D-Kleck))

##### Title:
Hunger Games: May the Odds Be Ever in Your Favor

##### Description:
A real-time multiplayer survival game, with basic game mechanics.

##### Vision Statement:
In order to provide a source of entertainment that is available to individuals
seeking to participate in larger collaborative gaming environments, Hunger
Games: May the Odds Be Ever in Your Favor is a game with a multiplayer feature.
It's a free for all, last man standing, Hunger Games style elimination game
where players play to survive in the Hunger Games. They can use any weapons and
gadgets at their disposal and the last player alive wins. May the odds be ever
in your favor!

##### Motivation:
We would like to learn about game development and familiarize ourselves with
creating software on a collaborative scale.

##### Risks:
- Group members may be unfamiliar with the technologies that are required for
  this project
- It may be difficult to find a universally adaptable solution for transporting
  data between servers and clients.
- Providing cross-platform or legacy browsers support may consume large amounts
  of time

##### Mitigation Strategy:
- Group members that are unfamiliar with involved technologies will attempt to
  learn more about the technology
- A modular approach to the components of this project will permit certain
  components to be omitted during development
- Starting early on the project, evaluation of pros/cons, and pacing the timing
  will mitigate the last two risks in the project

##### List of Requirements:
- User Requirements
- A decent computer and access to the Internet
- Functional Requirements
 - Web page
- Non-Functional Requirements
 - User Interface
 -  The game itself, with a 3D controled character that can attack by throwing knives.

##### Methodology:
We will be using an Agile approach for developing this project.
As a player, I want to play so that I can play with other friends online

##### Project Tracking Software:
GitHub Issues & Milestones

##### Organization:
All server related code is in the instance server repository
All the game related code and maps are in the game-client
##### Deployment:
The application can be run by cloning the game-client repository and building the project using Unity. To run the server, clone the instance-server repository and run `node lib/server.js`. The server will automatically run on port 3000, which the client is preset to connect to. The client can be run as a standalone client and will function in the absence of a server.


The issue tracker for the server can be found
[here](https://github.com/sdevgroup/instance-server/issues), and the client
[here](https://github.com/sdevgroup/game-client/issues).
