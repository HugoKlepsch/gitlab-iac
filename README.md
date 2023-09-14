# Gitlab docker-compose

Run a Gitlab server instance using docker-compose. This repo has all you need to
run a private Gitlab instance.

# Usage

- Edit `hostname` and `external_url` so that it matches the domain you want to host GitLab.
- Edit the port mappings so that Gitlab is exposed on the port that you want.
- You can now start the runner using `docker-compose up`, or create and start
the systemd service using `create-systemd-service.sh`.


