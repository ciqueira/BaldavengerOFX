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
| VideoGrade | OpenKey | [Get Key](https://get.mcnexus.app/baldavengerofx-videograde?utm_source=github&utm_medium=readme&utm_content=baldavengerofx-en) |
| HueConverge | OpenKey | [Get Key](https://get.mcnexus.app/baldavengerofx-hueconverge?utm_source=github&utm_medium=readme&utm_content=baldavengerofx-en) |
| FilmGrade | OpenKey | [Get Key](https://get.mcnexus.app/baldavengerofx-filmgrade?utm_source=github&utm_medium=readme&utm_content=baldavengerofx-en) |
| FreqSep | OpenKey | [Get Key](https://get.mcnexus.app/baldavengerofx-freqsep?utm_source=github&utm_medium=readme&utm_content=baldavengerofx-en) |
| FreqEQ | OpenKey | [Get Key](https://get.mcnexus.app/baldavengerofx-freqeq?utm_source=github&utm_medium=readme&utm_content=baldavengerofx-en) |
| Matrix | OpenKey | [Get Key](https://get.mcnexus.app/baldavengerofx-matrix?utm_source=github&utm_medium=readme&utm_content=baldavengerofx-en) |
| Qualifier | OpenKey | [Get Key](https://get.mcnexus.app/baldavengerofx-qualifier?utm_source=github&utm_medium=readme&utm_content=baldavengerofx-en) |
| Replace | OpenKey | [Get Key](https://get.mcnexus.app/baldavengerofx-replace?utm_source=github&utm_medium=readme&utm_content=baldavengerofx-en) |
| ResolveMath | OpenKey | [Get Key](https://get.mcnexus.app/baldavengerofx-resolvemath?utm_source=github&utm_medium=readme&utm_content=baldavengerofx-en) |
| ResolveMathxtra | OpenKey | [Get Key](https://get.mcnexus.app/baldavengerofx-resolvemathxtra?utm_source=github&utm_medium=readme&utm_content=baldavengerofx-en) |
| Scan | OpenKey | [Get Key](https://get.mcnexus.app/baldavengerofx-scan?utm_source=github&utm_medium=readme&utm_content=baldavengerofx-en) |
| SoftClip | OpenKey | [Get Key](https://get.mcnexus.app/baldavengerofx-softclip?utm_source=github&utm_medium=readme&utm_content=baldavengerofx-en) |

More plugins from the original suite may be added in future releases.

[Become a Supporter of the BaldavengerOFX Builds](https://buy.mcnexus.app/baldavenger-ofx-supporter?utm_source=github&utm_medium=readme&utm_content=baldavengerofx-en)

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

[Become a Supporter of the BaldavengerOFX Builds](https://buy.mcnexus.app/baldavenger-ofx-supporter?utm_source=github&utm_medium=readme&utm_content=baldavengerofx-en)

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
