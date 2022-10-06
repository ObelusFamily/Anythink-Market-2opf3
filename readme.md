# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup (for Macs)

1. Clone the Github repo. You can use the 'git clone' command for this.

2. Install Docker on your Mac.

3. Run 'docker -v' and 'docker-compose -v' in the terminal to check that Docker is installed.

4. Change directory ('cd') into the directory with the Github repo, and run 'sudo docker-compose up' to build the container and run the project.