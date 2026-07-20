# BaldavengerOFX for DaVinci Resolve

[English](README.md) · [Português](README.pt-BR.md)

Cross-platform builds of selected plugins from the BaldavengerOFX plugin suite
for DaVinci Resolve.

This fork provides independently maintained builds for macOS and Windows. The
plugins use Nexus services for distribution and technical-key association, and
the [MCNexus](https://mcnexus.app) app for downloads, updates,
and platform-specific installation.

The original BaldavengerOFX source was created by Paul Dore:
[baldavenger/BaldavengerOFX](https://github.com/baldavenger/BaldavengerOFX).
This fork and the support service provided by Magno Ciqueira are independent
and are not endorsed by or affiliated with the original author.

## Included Plugins

This build currently includes:

| Plugin | Distribution | Get Key |
| --- | --- | --- |
| VideoGrade | OpenKey | [Get Key](https://bridge.mcnexus.app/github/claim?t=baldavengerofx&tmpl=76bda215-5c6b-4a80-b35d-de4942ee0be6&sig=14aabec3a222872e) |
| HueConverge | OpenKey | [Get Key](https://bridge.mcnexus.app/github/claim?t=baldavengerofx&tmpl=c1ec264e-ccf9-4c9a-bfe0-180877bb3b2d&sig=ee04aca36d7d28ae) |
| FilmGrade | OpenKey | [Get Key](https://bridge.mcnexus.app/github/claim?t=baldavengerofx&tmpl=a5b1c083-a666-44fa-8948-12a94768ec9e&sig=ab4bb6e904a42a34) |
| FreqSep | OpenKey | [Get Key](https://bridge.mcnexus.app/github/claim?t=baldavengerofx&tmpl=61e768d4-4132-4bbb-ad5b-53cccc54b49f&sig=a82373ddfc7a19f8) |
| FreqEQ | OpenKey | [Get Key](https://bridge.mcnexus.app/github/claim?t=baldavengerofx&tmpl=c9bf68b5-ec7d-4b71-aa40-a9f19673adac&sig=929fab384d2224c8) |
| Matrix | OpenKey | [Get Key](https://bridge.mcnexus.app/github/claim?t=baldavengerofx&tmpl=79a22a0d-e988-495b-a319-d21bad22eb94&sig=da5e810a0191e9a0) |
| Qualifier | OpenKey | [Get Key](https://bridge.mcnexus.app/github/claim?t=baldavengerofx&tmpl=cc82944c-7b63-4a31-9618-43fda25d5f6f&sig=8c678dfce1b070e3) |
| Replace | OpenKey | [Get Key](https://bridge.mcnexus.app/github/claim?t=baldavengerofx&tmpl=002ef62d-b23b-4f32-89a3-db00e531b0ef&sig=3052a2dc5b32f16a) |
| ResolveMath | OpenKey | [Get Key](https://bridge.mcnexus.app/github/claim?t=baldavengerofx&tmpl=c60ebcca-5ceb-41c8-94ab-294ad70a76b2&sig=a29898eeebba5cca) |
| ResolveMathxtra | OpenKey | [Get Key](https://bridge.mcnexus.app/github/claim?t=baldavengerofx&tmpl=30be0b1a-da63-48da-b1fd-f3525654ebac&sig=93c6b132cd36df08) |
| Scan | OpenKey | [Get Key](https://bridge.mcnexus.app/github/claim?t=baldavengerofx&tmpl=f64c0dce-fcca-48f0-83a5-e3ef8dc6b565&sig=21a036b7e677ae07) |
| SoftClip | OpenKey | [Get Key](https://bridge.mcnexus.app/github/claim?t=baldavengerofx&tmpl=e31e7e72-ec9b-4558-8d92-6ce14c80693e&sig=42e9d4a461a0265c) |

More plugins from the original suite may be added in future releases.

[Become a Supporter of the BaldavengerOFX Builds](https://bridge.mcnexus.app/commerce/start?t=baldavengerofx&offer=baldavenger-ofx-supporter)

## Platform Support

Current builds are available for:

- macOS, including Intel Macs and Apple Silicon M-series processors
- Windows x64

Supported processing backends:

- Metal kernels on macOS for GPU-accelerated plugins
- CUDA kernels on Windows for NVIDIA GPU acceleration
- CPU kernels for CPU-only plugins such as ResolveMath and ResolveMathxtra

## Installation

The plugins use Nexus distribution services and the MCNexus app. Each plugin
has its own technical OpenKey record, even when multiple plugins are published
in the same release package. These records facilitate distribution and do not
replace or limit the GNU GPLv3 rights granted with the software.

Choose the plugin you want to install and claim the matching free key from the
table above.

## Activation Steps

1. Click the Get Key link for the plugin you want to use.
2. Authorize with your GitHub account.
3. Copy the generated license key.
4. Open MCNexus and activate the plugin with that key.
5. Install or update the plugin from MCNexus.

> Lost your key? Open the same claim link again with the same GitHub account to recover the same license.

## Support the BaldavengerOFX Builds

All listed plugins remain available under GNU GPLv3 without purchasing
support. If these builds are useful in your work, one optional BaldavengerOFX
builds support purchase covers every plugin currently listed in this README.

The Supporter benefit includes:

- priority private email support for 12 months, provided by Magno Ciqueira
  for these builds; and
- operational email notices about releases, compatibility, maintenance,
  security, and material changes to the builds and service.

Because this is a `support_only` offer, obtain at least one free BaldavengerOFX
key above before starting checkout. Separate plugin keys do not require
separate support purchases. Payment does not purchase the software, restrict
redistribution, add exclusive plugin features, or provide official support
from Paul Dore.

[Become a Supporter of the BaldavengerOFX Builds](https://bridge.mcnexus.app/commerce/start?t=baldavengerofx&offer=baldavenger-ofx-supporter)

These builds and the related support are independently maintained by **Magno
Ciqueira**. Distribution and technical keys use Nexus services, while MCNexus
is the app used to install and update the plugins.

Before purchasing, review the
[product terms](https://legal.magnociqueira.com.br/products/baldavenger-ofx/terms/),
[support policy](https://legal.magnociqueira.com.br/products/baldavenger-ofx/support/),
[privacy notice](https://legal.magnociqueira.com.br/products/baldavenger-ofx/privacy/),
and [cancellation and refund policy](https://legal.magnociqueira.com.br/products/baldavenger-ofx/refunds/).

## License and Corresponding Source

The fork remains licensed under the [GNU General Public License version 3](LICENSE).
Payment is not required to exercise the rights provided by that license.

The complete corresponding source for the binaries distributed through Nexus is
maintained in this repository. Each binary release must identify the source
tag or commit from which it was built. See [SOURCE.md](SOURCE.md),
[MODIFICATIONS.md](MODIFICATIONS.md), and [DISTRIBUTION.md](DISTRIBUTION.md).

## Credits

Original plugins and source:
Paul Dore / Baldavenger  
https://github.com/baldavenger/BaldavengerOFX

Nexus distribution and MCNexus/OpenKey integration:
Magno Ciqueira  
https://mcnexus.app
