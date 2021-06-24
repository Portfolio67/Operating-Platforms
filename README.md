# Operating-Platforms
Software design document
 The Gaming Room client had  software requirements that included:  The ability to log in to their gaming web based site, the ability for the server to populate images at 30 second intervals, the ability to host multiple clients. The client was the Gaming room, an online game that was the theme of a 80 hit game show. This client hosts a game on their server to many users across the globe.   The client wanted software designed to serve many clients, on multiple different platforms including mobile devises. This software has to be done efficiently and required a client server model with a hybrid cloud micro-service for the image retrieval.  The Language chosen  was java and swift, for the user side application to run on the users devises and access API`s for login, user management, social networking among players and logic of the game. 
 The thing I did best in developing the software design document, was the use of current software platform and architectures to date.  I also used many implementation examples, references and code snippets to guide the future build team.
 
The most helpful thing in the design document when designing the code was the image retrieval requirements.　This was helpful in deciding if a cloud was needed due to latency from regions and bandwidth of a central server.  The client server model was chosen and this, and was helpful to decide the code implementation of the APIs needed.

I wish I had more documentation on the new m1 chip from apple.  The architecture looks like something I wanted to use for the server.  There is many automated processes in Apple software, so there is not that many options to choose for the memory and storage management.

It is important to consider the users needs into the designs otherwise the game will not work as intended. If the game doesn’t work, there will be no users.  The need to populate information and file access of images on a time restraining manner. This is why a hybrid cloud Microservices was an option for the company.

The approach to designing the software was completed in a step-by-step process. I looked at the users experience and expectations for login to end of game play, and applied solutions accordingly. The strategy I will use in the future is, getting proficient in the best most modern System to use and apply the code accordingly.
