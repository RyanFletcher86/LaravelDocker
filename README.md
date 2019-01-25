# Introduction
Need a laravel development enviorment that just works with 1 command? I did too, that's why I created this GitHub repo.
LaravelDocker comes with 5.7 installed and working out of the box with it's default configuration. I've also included adminer,
which I have found useful as a lightweight interface to manage the mysql instance included with this package.

All you need to do is move your specific project's files into the laravel folder to get your own project files up and running.
If your starting from scratch, this repository should be all you need to get started.

## Prerequisites
All you need is the Docker Engine installed on your machine.

For Windows 10 Pro - Docker Desktop
For Windows 10 Home - https://docs.docker.com/toolbox/toolbox_install_windows/
For Mac - https://hub.docker.com/editions/community/docker-ce-desktop-mac

Most major linux distrubutions also contain a docker package in their repositories. See your distributions documentation for details.

## Running Instructions

1) Clone this repository
2) docker-compose up -d
3) browse to http://localhost
4) adminer is available at http://localhost:8080

## Found a problem? Need support?
Please file an issue in this repo's issue tracker. I'll do my best to keep this repository up to date and address any concerns or requests.