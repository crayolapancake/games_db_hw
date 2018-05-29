# games_db_hw

	•	What is responsible for defining the routes of the games resource?
		Request.js… or Games Router… unsure

	•	How is the server configured to know about the route definitions for the games resource?
		Server.js made up of index router and games router. Index router connects to DB 		to populate game with seed data.

	•	What is the responsibility of server.js?
		To direct url based on user input (path.join). To parse to Json.  Index router?

	•	What are the responsibilities of the indexRouter?
		Connects to database to seed collection of games

	•	What are the responsibilities of the gamesRouter?
		Deals with different url paths & connects to data based on what user inputs

	•	Which of the games API routes does the front-end application consume?
		Don’t understand question
