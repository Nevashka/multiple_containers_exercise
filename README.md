# Exercises
- Create a parent repo for a pair of services you have worked on eg. a client and a server
- Add the service repositories as submodules with `git submodule add <repo>`
- We recommend updating your resulting `.gitmodules` file to change the `url`s to to be relative instead of absolute eg. in this repo we updated `url = git@github.com:getfutureproof/mca-client.git` to `url = ../mca-client.git`
- Add a docker-compose.yaml configuration file to combine a previous project's client and api services
