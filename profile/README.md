<h1 align="center">VEOPS</h1>

<p align="center">
  <strong>Open-source tools for IT operations</strong>
</p>

<p align="center">
  <a href="https://veops.cn/">Website</a> ·
  <a href="https://veops.cn/docs/">Documentation</a> ·
  <a href="https://github.com/orgs/veops/repositories">Explore projects</a>
</p>

VEOPS develops open-source software for IT operations teams. Manage infrastructure assets with CMDB and control and audit access with OneTerm.

## Core projects

| Project | Description | Status |
| --- | --- | --- |
| [CMDB](https://github.com/veops/cmdb) | Configuration management database for IT assets, with custom models, resource discovery, and relationship views. | [![CMDB stars](https://img.shields.io/github/stars/veops/cmdb?style=flat-square)](https://github.com/veops/cmdb/stargazers) [![CMDB release](https://img.shields.io/github/v/release/veops/cmdb?style=flat-square)](https://github.com/veops/cmdb/releases) [![CMDB license](https://img.shields.io/github/license/veops/cmdb?style=flat-square)](https://github.com/veops/cmdb/blob/master/LICENSE) |
| [OneTerm](https://github.com/veops/oneterm) | Bastion host for secure infrastructure access, permission management, and session auditing. | [![OneTerm stars](https://img.shields.io/github/stars/veops/oneterm?style=flat-square)](https://github.com/veops/oneterm/stargazers) [![OneTerm release](https://img.shields.io/github/v/release/veops/oneterm?style=flat-square)](https://github.com/veops/oneterm/releases) [![OneTerm license](https://img.shields.io/github/license/veops/oneterm?style=flat-square)](https://github.com/veops/oneterm/blob/main/LICENSE) |

## Tools & libraries

| Project | Description | Status |
| --- | --- | --- |
| [OneOps-deploy](https://github.com/veops/OneOps-deploy) | Docker Compose deployment of CMDB and OneTerm, with ACL integrated into CMDB. | [![OneOps-deploy license](https://img.shields.io/github/license/veops/OneOps-deploy?style=flat-square)](https://github.com/veops/OneOps-deploy/blob/main/LICENSE) |
| [ACL](https://github.com/veops/acl) | Role-based access control with application-level permission isolation and a REST API. | [![ACL release](https://img.shields.io/github/v/release/veops/acl?style=flat-square)](https://github.com/veops/acl/releases) [![ACL license](https://img.shields.io/github/license/veops/acl?style=flat-square)](https://github.com/veops/acl/blob/main/LICENSE) |
| [messenger](https://github.com/veops/messenger) | Notification service for email, WeChat, Feishu, and DingTalk. | [![messenger license](https://img.shields.io/github/license/veops/messenger?style=flat-square)](https://github.com/veops/messenger/blob/main/LICENSE) |
| [ops-tools](https://github.com/veops/ops-tools) | Operations utilities for resource discovery, network topology, monitoring integration, and secrets management. | [![ops-tools license](https://img.shields.io/github/license/veops/ops-tools?style=flat-square)](https://github.com/veops/ops-tools/blob/main/LICENSE) |
| [go-ansiterm](https://github.com/veops/go-ansiterm) | VT-compatible terminal emulator in Go, with command extraction and ANSI escape sequence handling. | [![go-ansiterm license](https://img.shields.io/github/license/veops/go-ansiterm?style=flat-square)](https://github.com/veops/go-ansiterm/blob/main/LICENSE) |

Each project's license badge links to its license file.

## Get started

- Read the [CMDB documentation](https://veops.cn/docs/) for configuration and usage.
- Deploy CMDB and OneTerm together using the [OneOps-deploy setup guide](https://github.com/veops/OneOps-deploy#readme).
- Follow each project's README for standalone installation and local development.

## Contributing

Report bugs and request features in the relevant project's issue tracker. Include reproduction steps and environment details when reporting a bug. Submit code and documentation improvements through pull requests in that repository.
