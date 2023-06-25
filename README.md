podcast_and_a_collective_screencast_cast_to_a_github_repository_that_contains_a_collective_knolwledge



twitch - distributed podcast that shows many desktop computers. each (virtual desktop machine running on the server)  computer has a rust application that efficiently logs a screenshots when necessary

they get interlaced into twitch stream for the distribution purposes.

other OSS application that is installed on serveral GPU enabled machines reads the twitch stream, and uses a centralized public-write mongodb to pick a frames for analysis/store analysis results: OCR, 
LLM inference of the screenshots ("what is on this screenshot?", "what user wants to do?", "what is the next step for user?")