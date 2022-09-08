Introduction
========================
This repository is a home for snippets of YAML code and a sample hello world server of scripting for the Harness CI Community.

## Layout

The repository is broken up into four directories currently:

**[Docs](#Intro)**<br>
**[Harness Sample YAML](#Requirements)**<br>
**[Quickstart](#Quickstart)**<br>
**[Further Reading](docs/further_reading.md)**<br>
**[Build Instructions](docs/build.md)**<br>


## Getting Started

Use this README to get started with our sample pipeline repository for Nodejs. This guide outlines the basics of getting started with the Harness CI and provides a full code sample for you to try out.
This sample doesn’t include configuration options, for in depth steps and configuring the pipeline, for example, using triggers or using our templates, see the  [Pipeline Configuration Docs](#).

Here we have build a simple, two-stage CI Pipeline in Harness. Setting up and running the Pipeline will take about 30 minutes.
The Pipeline will build and run a unit test on a sample nodejs repository, upload the artifact to Docker Hub, and then run integration tests.
You can use publicly-available code, images, and your Github and Docker Hub accounts.
