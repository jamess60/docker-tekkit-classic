# CHANGELOG.md

## v6 (2025-06-16)
Features:

  - Rebased image from amazoncoretto to openjdk slim (Has halved the image size will still retaining amd64 and aarch64 support)
  - Add docker health check to image


## v5 (2025-04-22)
Features:

  - General update to base image (usp of the container...)
  

## v4 (2025-01-01)
Features:

  - General update to base image (usp of the container...)


## v3 (2024-10-31)
Features:

  - General update to base image (usp of the container...)
  - Added resource limits to docker compose example

Fix:

  - Remove version from docker compose example - deprecated tag
  - Tweak readme




## v2 (2024-05-05)
Fix:

  - Tekkit.jar console output now directs to /dev/null. The server.log file handle was open permanently causing /var/docker to fill the disk with > characters...


## v1 (2024-03-25)
Features:

  - Initial commit based on tekkit classic 3.1.2 (latest stable)

Fix:

  - Initial commit 

