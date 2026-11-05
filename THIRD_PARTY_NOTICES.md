# Third-party notices

This unofficial binary bundles third-party software. Copyright and license terms remain with their respective authors. The corresponding source snapshot is supplied with the release. The main OpenSCAD license and CGAL linking exception are in [COPYING](COPYING).

| Component | License / source |
| --- | --- |
| OpenSCAD | GPL-2.0-or-later with CGAL linking exception; [COPYING](COPYING), [upstream](https://github.com/openscad/openscad) |
| Qt 6 | LGPL-3.0-only or GPL-3.0-only (depending on module); [Qt licensing](https://www.qt.io/licensing/open-source-lgpl-obligations), [source](https://code.qt.io/cgit/qt/) |
| QScintilla | GPL-3.0-only; [source and license](https://www.riverbankcomputing.com/software/qscintilla/) |
| OpenCSG | GPL-2.0-or-later; [license](submodules/OpenCSG/copying.txt) |
| Manifold | Apache-2.0; [license](submodules/manifold/LICENSE) |
| Clipper2 | BSL-1.0; [license](submodules/Clipper2/LICENSE) |
| mimalloc | MIT; [license](submodules/mimalloc/LICENSE) |
| MCAD | LGPL-2.1; [source](https://github.com/openscad/MCAD) |

Other dynamically linked dependencies include Boost, GMP, MPFR, HarfBuzz, Fontconfig, GLib, gettext, libzip, OpenSSL, Cairo, FreeType, oneTBB, and their transitive dependencies. Their upstream source and license notices are available from the respective projects and Homebrew formulae. The binary uses dynamically linked Qt frameworks, which can be replaced by recipients with compatible builds.
