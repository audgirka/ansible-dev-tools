# Ansible Development Tools (ADT)

The `ansible-dev-tools` python package provides an easy way to install and discover the best tools available to create and test ansible content.

The curated list of tools installed as part of the Ansible automation developer tools package includes:

[ansible-core](https://github.com/ansible/ansible): Ansible is a radically simple IT automation platform that makes your applications and systems easier to deploy and maintain. Automate everything from code deployment to network configuration to cloud management, in a language that approaches plain English, using SSH, with no agents to install on remote systems.

[ansible-builder](https://github.com/ansible/ansible-builder): Ansible Builder is a tool that automates the process of building execution environments using the schemas and tooling defined in various Ansible Collections and by the user.

[ansible-creator](https://github.com/ansible/ansible-creator): The fastest way to generate all your ansible content!

[ansible-lint](https://github.com/ansible/ansible-lint): Checks playbooks for practices and behavior that could potentially be improved.

[ansible-navigator](https://github.com/ansible/ansible-navigator) A text-based user interface (TUI) for Ansible.

[ansible-sign](https://github.com/ansible/ansible-sign): Utility for signing and verifying Ansible project directory contents.

[molecule](https://github.com/ansible/molecule): Molecule aids in the development and testing of Ansible content: collections, playbooks and roles

[pytest-ansible](https://github.com/ansible/pytest-ansible): A pytest plugin that enables the use of ansible in tests, enables the use of pytest as a collection unit test runner, and exposes molecule scenarios using a pytest fixture.

[tox-ansible](https://github.com/ansible/tox-ansible): The tox-ansible plugin dynamically creates a full matrix of python interpreter and ansible-core version environments for running integration, sanity, and unit for an ansible collection both locally and in a Github action. tox virtual environments are leveraged for collection building, collection installation, dependency installation, and testing.

[ansible-dev-environment](https://github.com/ansible/ansible-dev-environment): A pip-like install for Ansible collections.

## Installation

`python -m pip install ansible-dev-tools`

## Usage

In addition to installing each of the above tools, `ansible-dev-tools` provides an easy way to show the versions of the content creation tools that make up the current development environment.

<!-- START -->

```
$ adt --version
ansible-builder                          3.0.0
ansible-core                             2.16.3
ansible-creator                          24.1.0
ansible-dev-environment                  24.1.0
ansible-dev-tools                        0.2.0a0
ansible-lint                             6.22.2
ansible-navigator                        24.2.0
ansible-sign                             0.1.1
molecule                                 6.0.3
pytest-ansible                           24.1.2
tox-ansible                              2.1.0
```

<!-- END -->

## Documentation

For more information, please visit our [documentation](https://ansible.readthedocs.io/projects/dev-tools/) page.
