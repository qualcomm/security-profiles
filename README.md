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
  <tr><td>Agatti</td><td>Kaanapali</td><td>Netrani</td></tr>
  <tr><td>Aldabra</td><td>Kailua</td><td>Nord</td></tr>
  <tr><td>Amboseli</td><td>Kalambo</td><td>Pakala</td></tr>
  <tr><td>Aspen</td><td>Kalpeni</td><td>Palawan</td></tr>
  <tr><td>Aurora</td><td>Kamorta</td><td>Palima</td></tr>
  <tr><td>Balsam</td><td>Kobuk</td><td>Pinnacles</td></tr>
  <tr><td>Bonito</td><td>Kodiak</td><td>Poros</td></tr>
  <tr><td>Bonsai</td><td>Kuno</td><td>Puna</td></tr>
  <tr><td>Cacao</td><td>Lahaina</td><td>Purwa</td></tr>
  <tr><td>Camano</td><td>Lanai</td><td>Rolas</td></tr>
  <tr><td>Clarence</td><td>Lassen</td><td>Sariska</td></tr>
  <tr><td>Divar</td><td>Lemans</td><td>Seca</td></tr>
  <tr><td>Eliza</td><td>Mahua</td><td>Shikra</td></tr>
  <tr><td>Fillmore</td><td>Maili</td><td>Skyros</td></tr>
  <tr><td>Firewheel</td><td>Matrix</td><td>Talos</td></tr>
  <tr><td>Glymur</td><td>Mavros</td><td>Tofino</td></tr>
  <tr><td>Halliday</td><td>Milos</td><td>Trenton</td></tr>
  <tr><td>Hamoa</td><td>Molokai</td><td>Waipio</td></tr>
  <tr><td>Hawi</td><td>Monaco</td><td>Wales</td></tr>
  <tr><td>Honu</td><td></td><td></td></tr>
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
