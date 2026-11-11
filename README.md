# Emissa: source code for its open-source components

Emissa is thermal measurement software made by Motrac Research Engineering Ltd. It ships with open-source
components, among them FFmpeg, which is licensed under the GNU General Public License. Some of those
licences (GPL, LGPL, MPL) entitle you to the corresponding source code. This repository is where Motrac
publishes it.

## Where the source code is

Each Emissa release has a matching release here, for example **emissa-0.1.0**. Its assets are the
source archives for that Emissa version, plus a `README.txt` that lists every archive with its licence and
SHA-256. The same archives are in the `sources` folder of the Emissa release folder.

The Emissa container image has its own release, named after the image's version, for example
**emissa-0.1.0-docker** for the image `emissa:0.1.0`. It holds the Debian source package of every Debian
package in the image (one `.tar` each, holding the `.dsc` and the files it names), the source of the
libraries bundled with OpenCV, `container-sources.txt` (the list of Debian source packages, also at
`/app/container-sources.txt` in the image) and a `README.txt`.

Some archives are marked as **known gaps** in that `README.txt`: the exact version or patches used in the
FFmpeg build could not be established, so the closest upstream release is provided. Motrac is working to
close these gaps.

The full list of open-source software in Emissa, with every licence text, is in Emissa under
**About → Open-source software**, and in `THIRD-PARTY-NOTICES.txt` in the Emissa release folder (`/app/THIRD-PARTY-NOTICES.txt` in the
container image).

## Written offer

Motrac Research Engineering Ltd will also supply the complete corresponding source code to anyone who asks, for at
least three years after Motrac last distributes the relevant version of Emissa, for no more than the cost
of physically providing it.

Motrac Research Engineering Ltd
B105 Thornton Science Park, Pool Lane, Ince, Chester, CH2 4NU, United Kingdom
Company no. 13542139
info@motracresearch.com · +44 1244 569517

Emissa itself is not open source. This repository holds only the third-party open-source components.
