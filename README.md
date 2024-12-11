
# Candidate-Search
The Candidate Search application allows users to explore a list of GitHub users and save potential candidates for further review.
Table of Contents

	•	Technologies Required
	•	Installation
	•	Usage
	•	Code Example
	•	Screenshots
	•	Features
	•	Planned Enhancements
	•	License
	•	Technologies
	•	Acknowledgments
	•	Contact Information
    Technologies Required

This application requires Node.js and its included package manager, npm.
You can download them from the official Node.js website. Follow the installation instructions provided.
Installation

	1.	Clone the repository and navigate to the project directory.
	2.	Open the terminal in the develop directory.
	3.	Run npm i to install all required dependencies.
	4.	Add a GitHub Fine-grained Personal Access Token to the .env.EXAMPLE file located in the develop/environment folder. Rename the file to .env.
	5.	Start the application using the command npm run dev.
    Usage

	•	Upon starting, the homepage will display a list of GitHub users (if a valid token is provided).
	•	Each user card includes their profile picture, username, and buttons for Accept or Decline. Additional information such as bio, name, email, location, or company (if available) is displayed.
	•	Clicking “Accept” will save a user to local storage and remove them from the list.
	•	Declining a user removes them from the list without saving.
	•	Saved candidates can be reviewed on the Saved Candidates page, accessible via a navigation link. Each saved user’s details can also be removed from storage on this page.
	•	A Clear Local Storage button on the homepage allows users to delete all saved candidates.
    Features

	•	View a list of GitHub users.
	•	Accept or decline users with interactive buttons.
	•	Save accepted users to local storage.
	•	Access and manage saved candidates from a dedicated page.
	•	Clear all saved candidates with a single button.
    Technologies

	•	Node.js: For installing packages and running the code.
	•	Vite: For running a local development server.
	•	Visual Studio Code: For code editing and debugging.
	•	Mozilla MDN and W3Schools: For JavaScript reference and guidance.
