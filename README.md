# ASP.NET 5 1.0.0-rc2 nightly-ish Preview Docker Image

This repository contains `Dockerfile` definitions for [ASP.NET 5](https://github.com/aspnet/home) Docker images and is a loose fork of the [ASP.NET 5 Preview Docker Image](https://github.com/aspnet/aspnet-docker) project.

[![Downloads from Docker Hub](https://img.shields.io/docker/pulls/sunside/aspnet.svg)](https://registry.hub.docker.com/u/sunside/aspnet)
[![Stars on Docker Hub](https://img.shields.io/docker/stars/sunside/aspnet.svg)](https://registry.hub.docker.com/u/sunside/aspnet)

## How to use this image

Please [read this article](http://blogs.msdn.com/b/webdev/archive/2015/01/14/running-asp-net-5-applications-in-linux-containers-with-docker.aspx) on .NET Web Development and Tools Blog to learn more about using this image.

This image provides the following environment variables:

* `DNX_USER_HOME`: path to DNX installation (e.g. /opt/dnx)
* `DNX_VERSION`: version of DNX (.NET Execution Environment) installed

In addition to these, `PATH` is set to include the `dnx`/`dnu` executables.
