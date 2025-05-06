####Self-Hosted Docker Runner for GitHub Actions####

From within this repo's directory (requires WSL if on Windows):

docker build -t runner-image .


Afterwards edit compose.yml to the configs you need.
Launch it with:

docker compose up


**Note: By default this runner builds a docker image with dotnet installed. Edit the Dockerfile if you need a different build system or need to pre-install other things.
