# Micronaut RxJava 1

[![Maven Central](https://img.shields.io/maven-central/v/io.micronaut.rxjava1/micronaut-rxjava1.svg?label=Maven%20Central)](https://search.maven.org/search?q=g:%22io.micronaut.rxjava1%22%20AND%20a:%22micronaut-rxjava1%22)
[![Build Status](https://github.com/micronaut-projects/micronaut-rxjava1/workflows/Java%20CI/badge.svg)](https://github.com/micronaut-projects/micronaut-rxjava1/actions)

Micronaut RxJava 1 adds legacy support for RxJava 1.x to Micronaut application.

## Documentation

See the [Documentation](https://micronaut-projects.github.io/micronaut-rxjava1/latest/guide/) for more information. 

See the [Snapshot Documentation](https://micronaut-projects.github.io/micronaut-rxjava1/snapshot/guide/) for the current development docs.

## Snapshots and Releases

Snaphots are automatically published to [JFrog OSS](https://oss.jfrog.org/artifactory/oss-snapshot-local/) using [Github Actions](https://github.com/micronaut-projects/micronaut-rxjava1/actions).

See the documentation in the [Micronaut Docs](https://docs.micronaut.io/latest/guide/index.html#usingsnapshots) for how to configure your build to use snapshots.

Releases are published to JCenter and Maven Central via [Github Actions](https://github.com/micronaut-projects/micronaut-rxjava1/actions).

A release is performed with the following steps:

* [Edit the version](https://github.com/micronaut-projects/micronaut-rxjava1/edit/master/gradle.properties) specified by `projectVersion` in `gradle.properties` to a semantic, unreleased version. Example `1.0.0`
* [Create a new release](https://github.com/micronaut-projects/micronaut-rxjava1/releases/new). The Git Tag should start with `v`. For example `v1.0.0`.
* [Monitor the Workflow](https://github.com/micronaut-projects/micronaut-rxjava1/actions?query=workflow%3ARelease) to check it passed successfully.
* Celebrate!
