# Developer Setup Guide

This section is a step-by-step instruction on how to configure your development environment.

## VS Code

Using VS Code as our editor has some benefits over using Visual Studio. Because our project is a
[monorepo](https://en.wikipedia.org/wiki/Monorepo) consisting of projects with various programming languages, build
systems, package managers, code analysis tools (etc.), we need a versatile and configurable editor.

Download and install VS Code [here](https://code.visualstudio.com/download).

## Docker

To perfectly emulate the production host environment, we are *containerizing* our application with Docker.

Docker Desktop, using the docker runtime for Linux, does the heavy lifting on a Windows machine to build and run a Linux
[runtime environment](https://en.wikipedia.org/wiki/Runtime_system) that is identical to the runtime environment created
for hosting in the cloud. This way, whatever works or breaks on your laptop will work or break in production.

Learn more about Docker [here](https://www.docker.com/).

Download and install Docker Desktop [here](https://www.docker.com/products/docker-desktop/).

## Node

Node is a general-purpose Javascript runtime. We are using Node for a few reasons. Node's project structuring system is
helpful for monorepos like this one, allowing multilayered projects, scripts, and packages. We'll also be using Node to
create our frontend [web](../web/) project.

Learn more about Node [here](https://nodejs.org/en).

Download and install Node [here](https://nodejs.org/en/download/package-manager).

> Please make sure to download and install version 20.16.0.
