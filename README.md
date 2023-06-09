# OpenTelemetry-eBPF Build Tools

This repository contains third-party tools and libraries needed to build
projects in the [opentelemetry-ebpf](https://github.com/open-telemetry/opentelemetry-ebpf)
repository.

Building this repository results in a _build environment_ container image that
is then used for building artifacts of the main project (see the
[Developer Guilde](https://github.com/open-telemetry/opentelemetry-ebpf/blob/main/docs/developing.md)).

## MacOS prerequisites:

* The ["Homebrew"](https://brew.sh/) package manager
* [Docker Desktop](https://hub.docker.com/editions/community/docker-ce-desktop-mac)
* cmake: `brew install cmake`
* make: installed along with developer tools; if Homebrew is working you should have make

## Building

* Check out this repository
* Run the build script: `./build.sh`

## Adding a new dependency

Use `add_dependency.sh` and follow instructions.

## Contributing ##

Maintainers ([@open-telemetry/ebpf-maintainers](https://github.com/orgs/open-telemetry/teams/ebpf-maintainers)):

- [Borko Jandras](https://github.com/bjandras), Splunk
- [Jim Wilson](https://github.com/jimwsplk), Splunk
- [Jonathan Perry](https://github.com/yonch), Splunk

Learn more about roles in the [community repository](https://github.com/open-telemetry/community/blob/main/community-membership.md).
