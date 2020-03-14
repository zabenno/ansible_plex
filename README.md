# Overview
This role sets up a plex container.

# Assumptions
* Docker networking mode fits the use case.
* A valid claim token will be given everytime this role is run.
* Paths to volumes default to `/var/plex` on the host with `db, transcode, and media` being sub-directories.
* Latest container is desired.
* The following ports are available: 32400/tcp, 3005/tcp, 8324/tcp, 32469/tcp, 1900/udp, 32410/udp, 32412/udp, 32413/udp, 32414/udp.
