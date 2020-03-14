# Overview
This role sets up a plex container.

# Assumptions
* Docker networking mode fits the use case.
* A valid claim token will be given everytime this role is run.
* Paths to volumes default to `/var/plex` on the host with `db, transcode, and media` being sub-directories.
* Latest container is desired.
