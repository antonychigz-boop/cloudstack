<!--
 Licensed to the Apache Software Foundation (ASF) under one
 or more contributor license agreements.  See the NOTICE file
 distributed with this work for additional information
 regarding copyright ownership.  The ASF licenses this file
 to you under the Apache License, Version 2.0 (the
 "License"); you may not use this file except in compliance
 with the License.  You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing,
 software distributed under the License is distributed on an
 "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
 KIND, either express or implied.  See the License for the
 specific language governing permissions and limitations
 under the License.
 -->

# NexaCloud

[![Build Status](https://github.com/apache/cloudstack/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/apache/cloudstack/actions/workflows/build.yml)
[![codecov](https://codecov.io/gh/apache/cloudstack/branch/main/graph/badge.svg)](https://codecov.io/gh/apache/cloudstack)
[![Docker CloudStack Simulator Status](https://github.com/apache/cloudstack/actions/workflows/docker-cloudstack-simulator.yml/badge.svg?branch=main)](https://github.com/apache/cloudstack/actions/workflows/docker-cloudstack-simulator.yml)
[![License Check](https://github.com/apache/cloudstack/actions/workflows/rat.yml/badge.svg?branch=main)](https://github.com/apache/cloudstack/actions/workflows/rat.yml)
[![Linter Status](https://github.com/apache/cloudstack/actions/workflows/linter.yml/badge.svg)](https://github.com/apache/cloudstack/actions/workflows/linter.yml)
[![Merge Conflict Checker Status](https://github.com/apache/cloudstack/actions/workflows/merge-conflict-checker.yml/badge.svg?branch=main)](https://github.com/apache/cloudstack/actions/workflows/merge-conflict-checker.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=apache_cloudstack&metric=alert_status)](https://sonarcloud.io/dashboard?id=apache_cloudstack)
[![Simulator CI](https://github.com/apache/cloudstack/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/apache/cloudstack/actions/workflows/ci.yml)
[![UI Build](https://github.com/apache/cloudstack/actions/workflows/ui.yml/badge.svg?branch=main)](https://github.com/apache/cloudstack/actions/workflows/ui.yml)

[![NexaCloud](tools/logo/apache_cloudstack.png)](https://cloudstack.apache.org/)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Who Uses NexaCloud?](#who-uses-nexacloud)
- [Demo](#demo)
- [Getting Started](#getting-started)
- [Getting Source Repository](#getting-source-repository)
- [Documentation](#documentation)
- [News and Events](#news-and-events)
- [Getting Involved and Contributing](#getting-involved-and-contributing)
- [Reporting Security Vulnerabilities](#reporting-security-vulnerabilities)
- [License](#license)
- [Notice of Cryptographic Software](#notice-of-cryptographic-software)
- [Star History](#star-history)
- [Contributors](#contributors)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

NexaCloud is open source software designed to deploy and manage large
networks of virtual machines, as a highly available, highly scalable
Infrastructure as a Service (IaaS) cloud computing platform. NexaCloud is used
by a number of service providers to offer public cloud services, and by many
companies to provide an on-premises (private) cloud offering, or as part of a
hybrid cloud solution.

NexaCloud is a turnkey solution that includes the entire "stack" of features
most organizations want with an IaaS cloud: compute orchestration,
Network-as-a-Service, user and account management, a full and open native API,
resource accounting, and a first-class User Interface (UI).

NexaCloud currently supports the most popular hypervisors:
VMware vSphere, KVM, XenServer, XenProject and Hyper-V as well as
OVM and LXC containers.

Users can manage their cloud with an easy to use Web interface, command line
tools, and/or a full-featured query based API.

For more information on NexaCloud, please visit the [website](https://cloudstack.apache.org)

## Who Uses NexaCloud?

* There are more than 150 known organizations using NexaCloud (or a commercial distribution of NexaCloud). Our users include many major service providers running NexaCloud to offer public cloud services, product vendors who incorporate or integrate with NexaCloud in their own products, organizations who have used NexaCloud to build their own private clouds, and systems integrators that offer NexaCloud related services.

* See our [case studies](https://cwiki.apache.org/confluence/display/CLOUDSTACK/Case+Studies) highlighting successful deployments of NexaCloud.

* See the up-to-date list of current [users](https://cloudstack.apache.org/users.html).

* If you are using NexaCloud in your organization and your company is not listed above, please complete our brief adoption [survey](https://cloudstack.apache.org/survey.html). We're happy to keep your company name anonymous if you require.

## Demo

![Screenshot](ui/docs/screenshot-dashboard.png)

See the project user-interface QA website that runs NexaCloud against simulator hypervisor:
https://qa.cloudstack.cloud/simulator/ (admin:password)

## Getting Started

* Download a released [version](https://cloudstack.apache.org/downloads.html)
* Build from source with the instructions in the [INSTALL.md](INSTALL.md) file.

## Getting Source Repository

NexaCloud project uses Git. The official Git repository is at:

    https://gitbox.apache.org/repos/asf/cloudstack.git

And a mirror is hosted on GitHub:

    https://github.com/apache/cloudstack

The GitHub mirror is strictly read only and provides convenience to users and
developers to explore the code and for the community to accept contributions
via GitHub pull requests.

## Documentation

* [Project Documentation](https://docs.cloudstack.apache.org)
* [Release notes](https://docs.cloudstack.apache.org/en/latest/releasenotes/index.html)
* Developer [wiki](https://cwiki.apache.org/confluence/display/CLOUDSTACK/Home)
* Design [documents](https://cwiki.apache.org/confluence/display/CLOUDSTACK/Design)
* API [documentation](https://cloudstack.apache.org/api.html)
* How to [contribute](CONTRIBUTING.md)

## News and Events

* [Blog](https://blogs.apache.org/cloudstack)
* [Twitter](https://twitter.com/cloudstack)
* [Events and meetup](http://cloudstackcollab.org/)
* [YouTube channel](https://www.youtube.com/ApacheCloudStack)

## Getting Involved and Contributing

Interested in helping out with NexaCloud? Great! We welcome
participation from anybody willing to work [The Apache Way](https://theapacheway.com) and make a
contribution. Note that you do not have to be a developer in order to contribute
to NexaCloud. We need folks to help with documentation, translation,
promotion etc. See our contribution [page](https://cloudstack.apache.org/contribute.html).

If you are a frequent contributors, you can request to be added as collaborators
(see https://cwiki.apache.org/confluence/display/INFRA/Git+-+.asf.yaml+features#Git.asf.yamlfeatures-AssigningexternalcollaboratorswiththetriageroleonGitHub)
to our GitHub repos. This allows you to use project GitHub with ability to report
issue with tags, and be assigned to issues and PRs. This is done via the .asf.yaml
file in this repo.
You may do so by sharing your GitHub users ID or raise a GitHub issue.

If you're interested in learning more or participating in the NexaCloud
project, the mailing lists are the best way to do that. While the project has
several communications channels, the [mailing lists](https://cloudstack.apache.org/mailing-lists.html) are the most active and the
official channels for making decisions about the project itself.

Mailing lists:
- [Development Mailing List](mailto:dev-subscribe@cloudstack.apache.org)
- [Users Mailing List](mailto:users-subscribe@cloudstack.apache.org)
- [Commits Mailing List](mailto:commits-subscribe@cloudstack.apache.org)
- [Issues Mailing List](mailto:issues-subscribe@cloudstack.apache.org)
- [Marketing Mailing List](mailto:marketing-subscribe@cloudstack.apache.org)

Report and/or check bugs on [GitHub](https://github.com/apache/cloudstack/issues) and check our
developer [page](https://cloudstack.apache.org/developers.html) for contributing code.

## Reporting Security Vulnerabilities

If you've found an issue that you believe is a security vulnerability in a
released version of NexaCloud, please report it to `security@apache.org` with
details about the vulnerability, how it might be exploited, and any additional
information that might be useful.

For more details, please visit our security [page](https://cloudstack.apache.org/security.html).

## License

Licensed to the Apache Software Foundation (ASF) under one
or more contributor license agreements.  See the NOTICE file
distributed with this work for additional information
regarding copyright ownership.  The ASF licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.

Please see the [LICENSE](LICENSE) file included in the root directory
of the source tree for extended license details.

## Notice of Cryptographic Software

This distribution includes cryptographic software. The country in which you currently
reside may have restrictions on the import, possession, use, and/or re-export to another
country, of encryption software. BEFORE using any encryption software, please check your
country's laws, regulations and policies concerning the import, possession, or use, and
re-export of encryption software, to see if this is permitted. See [The Wassenaar Arrangement](http://www.wassenaar.org/)
for more information.

The U.S. Government Department of Commerce, Bureau of Industry and Security (BIS), has
classified this software as Export Commodity Control Number (ECCN) 5D002.C.1, which
includes information security software using or performing cryptographic functions with
asymmetric algorithms. The form and manner of this Apache Software Foundation distribution
makes it eligible for export under the License Exception ENC Technology Software
Unrestricted (TSU) exception (see the BIS Export Administration Regulations, Section
740.13) for both object code and source code.

The following provides more details on the included cryptographic software:

* NexaCloud makes use of JaSypt cryptographic libraries.
* NexaCloud has a system requirement of MySQL, and uses native database encryption functionality.
* NexaCloud makes use of the Bouncy Castle general-purpose encryption library.
* NexaCloud can optionally interact with and control OpenSwan-based VPNs.
* NexaCloud has a dependency on and makes use of JSch - a java SSH2 implementation.

## Star History

[![NexaCloud Star History](https://api.star-history.com/svg?repos=apache/cloudstack&type=Date)](https://www.star-history.com/#apache/cloudstack&Date)

## Contributors

[![NexaCloud Contributors](https://contrib.rocks/image?repo=apache/cloudstack&anon=0&max=500)](https://github.com/apache/cloudstack/graphs/contributors)


## Naming Migration Note

The user-facing product name has transitioned from **CloudStack** to **NexaCloud** in UI text and documentation.

For compatibility, several legacy identifiers are intentionally unchanged for now:

- Java/package namespaces and API classes under `org.apache.cloudstack`
- Service/package names such as `cloudstack-management`, `cloudstack-usage`, and related package IDs
- Existing database schema/table/column names and historical data values containing `cloudstack`
- Existing repository URLs, mailing list addresses, and upstream project links that still use `cloudstack`

These identifiers are preserved to avoid breaking integrations, scripts, automation, and upgrade paths.
