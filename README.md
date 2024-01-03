![](https://img.shields.io/badge/STATUS-NOT%20CURRENTLY%20MAINTAINED-red.svg?longCache=true&style=flat)

# Important Notice
This public repository is read-only and no longer maintained.

# Description

An efficient software development process is vital for success in building
business applications on SAP Cloud Platform or SAP on-premise platforms. SAP
addresses this need for efficiency with project "Piper". The goal of project
"Piper" is to substantially ease setting up continuous delivery processes for
the most important SAP technologies by means of Jenkins pipelines.

Project "Piper" consists of two parts:

* [A shared library][piper-library] containing steps and utilities that are
  required by Jenkins pipelines.
* A set of [Docker images][devops-docker-images] used in the piper library to
  implement best practices.

Please follow [this link to our extended library documentation][piper-library-pages].

## Integration Testing

As project "Piper" itself is a software project, the CI/CD and DevOps principles are also 
valid for it.
A third part of project "Piper" is this test repository, containing parts of the integration test
control flow. This control flow scripts have an own lifecycle and should not be part of the 
library but are an important part of the project "Piper" ecosystem.

Here you can find the corresponding [test cases][consumer-tests]

# Integration Test Results

Before merged into master, each pull request has to be integration tested. The integration test results
can be checked at the [pull requests][piper-library-pulls] 


# Known Issues

A list of known issues is available on the [GitHub issues page of this
project][piper-library-test-issues].

# How to obtain support

Feel free to open new issues for feature requests, bugs or general feedback on
the [GitHub issues page of this project][piper-library-test-issues].

Register to our [google group][google-group] in order to get updates or for asking questions.

# Contributing

Read and understand our [contribution guidelines][piper-library-test-contribution]
before opening a pull request.

# [License][piper-library-test-license]

Copyright (c) 2019-2021 SAP SE or an SAP affiliate company. All rights reserved.
This file is licensed under the Apache Software License, v. 2 except as noted
otherwise in the [LICENSE file][piper-library-test-license]. Detailed information
including third-party components and their licensing/copyright information is
available [via the REUSE tool][reuse-tool].

[github]: https://github.com
[piper-library]: https://github.com/SAP/jenkins-library
[piper-library-pulls]: https://github.com/SAP/jenkins-library/pulls
[devops-docker-images]: https://github.com/SAP/devops-docker-images
[consumer-tests]: https://github.com/SAP/jenkins-library/tree/master/consumer-test
[piper-library-pages]: https://sap.github.io/jenkins-library
[piper-library-test-issues]: https://github.com/SAP/jenkins-library-test/issues
[piper-library-test-license]: ./LICENSE
[piper-library-test-contribution]: .github/CONTRIBUTING.md
[google-group]: https://groups.google.com/forum/#!forum/project-piper
[reuse-tool]: https://api.reuse.software/info/github.com/SAP/jenkins-library-test
