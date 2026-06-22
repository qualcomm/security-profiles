# Security Profiles

Central repository for Qualcomm Security Profile XML files used by the Sectools image signing and verification infrastructure across Qualcomm® SoC platforms.

Each Security Profile defines per-chipset authentication, image signing, debug policy, and platform binding configuration consumed by Sectools during image builds.

## Downloading Sectools V2

Sectools V2 can be downloaded from the [Qualcomm Software Center](https://softwarecenter.qualcomm.com/catalog/item/Qualcomm_Security_Tools).

Once installed, use the following command to list available features and learn how each one interacts with Security Profiles:

```bash
sectools <feature> --help
```

For example:

The `--help` output for each feature describes the expected Security Profile arguments, supported options, and usage examples relevant to that feature.

## Supported Targets

The repository currently contains Security Profiles for the following targets:

<table>
  <tr><td>Kodiak</td><td>LeMans</td><td>Talos</td></tr>
</table>

## Getting in Contact

* [Report an Issue on GitHub](../../issues)
* [Open a Discussion on GitHub](../../discussions)

## License

Security Profiles is licensed under the [BSD-3-clause License](https://spdx.org/licenses/BSD-3-Clause.html). See [LICENSE.txt](LICENSE.txt) for the full license text.


**After repository creation:**
- [ ] Update this `README.md`. Update the Project Name, description, and all sections. Remove this checklist.
- [ ] If required, update `LICENSE.txt` and the License section with your project's approved license
- [ ] Search this repo for "REPLACE-ME" and update all instances accordingly
- [ ] Update `CONTRIBUTING.md` as needed
- [ ] Review the workflows in `.github/workflows`, updating as needed. See https://docs.github.com/en/actions for information on what these files do and how they work.
- [ ] Review and update the suggested Issue and PR templates as needed in `.github/ISSUE_TEMPLATE` and `.github/PULL_REQUEST_TEMPLATE`

# Project Name

*\<update with your project name and a short description\>*

Project that does ... implemented in ... runs on Qualcomm® *\<processor\>*

## Branches

**main**: Primary development branch. Contributors should develop submissions based on this branch, and submit pull requests to this branch.

## Requirements

List requirements to run the project, how to install them, instructions to use docker container, etc...

## Installation Instructions

How to install the software itself.

## Usage

Describe how to use the project.

## Development

How to develop new features/fixes for the software. Maybe different than "usage". Also provide details on how to contribute via a [CONTRIBUTING.md file](CONTRIBUTING.md).

## Getting in Contact

How to contact maintainers. E.g. GitHub Issues, GitHub Discussions could be indicated for many cases. However a mail list or list of Maintainer e-mails could be shared for other types of discussions. E.g.

* [Report an Issue on GitHub](../../issues)
* [Open a Discussion on GitHub](../../discussions)
* [E-mail us](mailto:REPLACE-ME@qti.qualcomm.com) for general questions

## License

*\<update with your project name and license\>*

*\<REPLACE-ME\>* is licensed under the [BSD-3-clause License](https://spdx.org/licenses/BSD-3-Clause.html). See [LICENSE.txt](LICENSE.txt) for the full license text.
