# Oracle Cloud Infrastructure Ansible Modules (Legacy)

## Deprecation Notice

**The new [OCI Ansible collection](https://github.com/oracle/oci-ansible-collection), replaces [legacy OCI Ansible modules](https://github.com/oracle/oci-ansible-modules).**

- Please migrate to the new OCI Ansible collection for improved features and support.
  Refer to the [Migration Guide](https://github.com/oracle/oci-ansible-collections/blob/master/MigrationGuide.md) for best migration practices.
- These legacy modules will be available only in the maintenance mode and only critical bugs will be fixed.
  **They will be deprecated on 1st May 2021.**

## About

Oracle Cloud Infrastructure Ansible Modules provide an easy way to create and provision resources in Oracle Cloud Infrastructure (OCI) through Ansible. These modules allow you to author Ansible playbooks that help you automate the provisioning and configuring of Oracle Cloud Infrastructure services and resources, such as Compute, Load Balancing, Database, and other Oracle Cloud Infrastructure services.

**Services supported**

- Block Volume
- Compute
- Container Engine for Kubernetes Service (OKE)
- Database (including support for Autonomous Transaction Processing and Autonomous Data Warehouse Services)
- Edge Services (DNS, WAF)
- IAM
- Load Balancing
- Networking
- Object Storage
- File Storage
- Email Delivery
- Search

The OCI Ansible modules are built using the [Oracle Cloud Infrastructure Python SDK](https://docs.us-phoenix-1.oraclecloud.com/Content/API/SDKDocs/pythonsdk.htm). The OCI Ansible modules honour the [SDK configuration](https://docs.us-phoenix-1.oraclecloud.com/Content/ToolsConfig.htm) when available.

## Installation

There are two methods for installation:

#### 1) Installation Script

Clone the modules from Github then use install.py script.

Note: This installation method will not be supported in Ansible 2.10.

![](docs/quick-install.gif)

## Samples

This project includes a catalog of Oracle Cloud Infrastructure Ansible module samples that illustrate using the modules to carry out common infrastructure provisioning and configuration tasks.
The samples are organized in groups associated with Oracle Cloud Infrastructure services under [the samples directory on GitHub](https://github.com/oracle/oci-ansible-modules/tree/master/samples).

Begin by reviewing the Readme.md file that you will find in each sample's root directory.

## Documentation

Documentation to get started and details about prerequisites, installation and configuration instructions, can be found [here](https://docs.cloud.oracle.com/iaas/Content/API/SDKDocs/ansible.htm).

## Help

See the ["Questions or Feedback”](https://docs.cloud.oracle.com/iaas/Content/API/SDKDocs/ansible.htm) section.

## Changes

See [CHANGELOG](https://github.com/oracle/oci-ansible-modules/blob/master/CHANGELOG.md).

## Contributing

`oci-ansible-modules` is an open source project. See [CONTRIBUTING](https://github.com/oracle/oci-ansible-modules/blob/master/CONTRIBUTING.md) for details.

Oracle gratefully acknowledges the contributions to `oci-ansible-modules` that have been made by the community.

## Known Issues

You can find information on any known issues with OCI [here](https://docs.us-phoenix-1.oraclecloud.com/Content/knownissues.htm) and known issues with the OCI Ansible Modules under the “Issues” tab of this project's [GitHub repository](https://github.com/oracle/oci-ansible-modules).

## License

Copyright (c) 2018, 2020, Oracle and/or its affiliates.

This software is made available to you under the terms of the GPL 3.0 license or the Apache 2.0 license.

See [LICENSE.txt](https://github.com/oracle/oci-ansible-modules/blob/master/LICENSE.txt) for more details.
