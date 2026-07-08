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
The following <a href="https://dragonwingdocs.qualcomm.com/index" style="text-decoration: none !important; font-weight: bold;">Qualcomm Dragonwing™</a> targets are currently supported by the Security Profiles in this repository

<table>
  <thead>
    <tr>
      <th>SoC</th>
      <th>Description</th>
      <th>Security Profile</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="3">QCS6490</td>
      <td>Qualcomm Dragonwing™ RB3 Gen 2 Vision Kit</td>
      <td rowspan="5">kodiak_security_profile.xml</td>
    </tr>
    <tr>
      <td>Qualcomm Dragonwing™ RB3 Gen 2 Core Kit</td>
    </tr>
    <tr>
      <td>Qualcomm Dragonwing™ RB3 Gen 2 Industrial Kit</td>
    </tr>
    <tr>
      <td rowspan="2">QCS5430</td>
      <td>Qualcomm Dragonwing™ RB3 Gen 2 Lite Vision Kit</td>
    </tr>
    <tr>
      <td>Qualcomm Dragonwing™ RB3 Gen 2 Lite Core Kit</td>
    </tr>
    <tr>
      <td>IQ9</td>
      <td>Qualcomm Dragonwing™ IQ-9075 Evaluation Kit</td>
      <td>lemans_security_profile.xml</td>
    </tr>
    <tr>
      <td>IQ8</td>
      <td>Qualcomm Dragonwing™ IQ-8275 Evaluation Kit</td>
      <td>monaco_security_profile.xml</td>
    </tr>
    <tr>
      <td>IQ6</td>
      <td>Qualcomm Dragonwing™ IQ-615 Evaluation Kit</td>
      <td>talos_security_profile.xml</td>
    </tr>
  </tbody>
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
