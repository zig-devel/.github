# Zig Devel — a collection of C libraries built with Zig Build

This collection is inspired by
[AUR](https://aur.archlinux.org/),
[Bazel Registry](https://registry.bazel.build/), and the
[All Your Codebase project](https://github.com/allyourcodebase).
All projects here are builded, tested, published, documented, and licensed identically.

**Tests:** library has smoke test that checks that the code at least links correctly.
CI checks cross-compilation for all OS supported by Zig:
Windows, Linux, MacOS, FreeBSD and NetBSD.

**License:** library licensed under both the 0BSD license and the original project
license, so as not to impose any additional restrictions.

**Release:** library versions are pushed to an immutable GitHub Release,
you can be sure that v1.42.0 points to the same commit in all your repositories.

**Updates:** Automated checks for new versions in upstream every 3 hours.
