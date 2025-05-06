####Self-Hosted Docker Runner for GitHub Actions####

From within this repo's directory (requires WSL if on Windows):

docker build -t runner-image .


Afterwards edit compose.yml to the configs you need.
Launch it with:

docker compose up

