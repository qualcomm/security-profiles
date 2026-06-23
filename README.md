# Security Profiles

Central repository for Qualcomm Security Profile XML files used by the Sectools image signing and verification infrastructure across Qualcomm® SoC platforms.

Each Security Profile defines per-chipset authentication, image signing, debug policy, and platform binding configuration consumed by Sectools during image builds.

<br>

## Downloading Sectools V2

Sectools V2 can be downloaded from the [Qualcomm Software Center](https://softwarecenter.qualcomm.com/catalog/item/Qualcomm_Security_Tools).

Once installed, use the following command to list available features and learn how each one interacts with Security Profiles:

```bash
sectools <feature> --help
```

For example:

The `--help` output for each feature describes the expected Security Profile arguments, supported options, and usage examples relevant to that feature.

<br>

## Supported Targets

The repository currently contains Security Profiles for the following targets:

<table>
  <tr><td>Kodiak</td><td>LeMans</td><td>Talos</td></tr>
</table>

<br>

## Development
Thank you for your interest, but contributions to this project are currently not being accepted.

<br>

## Getting in Contact

* [Report an Issue on GitHub](../../issues)
* [Open a Discussion on GitHub](../../discussions)

<br>

## License

Security Profiles is licensed under the [BSD-3-clause-clear License](https://spdx.org/licenses/BSD-3-Clause-Clear.html). See [LICENSE.txt](LICENSE.txt) for the full license text.

<br>
