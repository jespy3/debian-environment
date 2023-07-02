# debian-environment

Copy this repo to have a good foundational docker-based go scripting environment using a command like:
```
git clone git@github.com:jespy3/debian-environment.git new-repo-name
cp -r ./go-scripting-environment ./new-repo-name
cd new-repo-name
rm -rf .git      # to disassociate the 'debian-environment' git files
```

## Setup

Ensure `docker compose` is available on current version of docker.

Run
```
docker compose up -d
```

Then
```
docker compose exec box bash
```

## Running the script

In the container, run:
```
```
