# Unofficial OpenSCAD macOS arm64 build

This repository contains OpenSCAD source code from the [OpenSCAD project](https://github.com/openscad/openscad). The macOS arm64 binary in the accompanying release is an **unofficial community build**, not an OpenSCAD project release or an Apple-notarized app.

The application was built on an Apple M1 Pro running macOS 27.3 with Xcode 27.2 and Qt 6.12. The binary is arm64 only, targets macOS 12.0 or later, and reports `OpenSCAD 2026.11.04`. That version string is the local build date, not an official OpenSCAD release number. The build includes CGAL and Manifold. It does **not** include lib3mf, so 3MF import and export are unavailable.

The app is ad-hoc signed. The bundled frameworks and dynamic libraries are inside the `.app`; the build was checked for references to Homebrew paths and tested on macOS 27.3 by opening the GUI and exporting an STL. Apple notarization has not been performed.

## Source and licensing

OpenSCAD's original copyright and license notices are retained. The main program is licensed under GPL-2.0-or-later; see [COPYING](COPYING). The source package attached to the release contains the source snapshot used for this binary, including the vendored source of the required submodules. Third-party components and their license locations are summarized in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md). Recipients may inspect, rebuild, and modify the source under its applicable licenses.

This distribution is not affiliated with or endorsed by the OpenSCAD developers. For official downloads, see [openscad.org](https://openscad.org/downloads.html).

## Verify the download

On macOS, run `shasum -a 256 OpenSCAD-arm64-macOS27.dmg` and compare the result with `SHA256SUMS` in the release.
