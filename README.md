# Docker-Base
This a project to copy.

This repo contains php, mysql and nginx. You can change version of this by the git submodules. If version not existing as tag do a pull request inside the submodule.

# Install

Since this repo is hard copied, the installation instructions can be found in the [wiki](https://github.com/freedmo/Docker-Base/wiki/Installation) of this repo.

# docker-sync

Change `PROJECTNAME` see [wiki](https://github.com/freedmo/Docker-Base/wiki/Installation) and `sync_userid` in `docker-sync.yml` to your user id unix/linux.

If you want use run `docker-sync run` after it start docker by `docker-compose -f docker-compose.yml -f docker-compose-dev.yml up -d`.