# ys-3dskit

3DSKIT IS NOW EOL AS OF 2025-05-22.

ys-3dskit is a set of tools to get you writing 3DS homebrew easier and faster.

It comes with the following main features:

- use of [xmake](https://xmake.io) as the build tool, for easier to understand builds
- use of xmake's package management to install 3ds libraries, instead of devkitpro pacman
- support for [the D programming language](https://dlang.org/) for writing your 3DS applications,
  in addition to C and C++.
   * D bindings for all packages in the 3dskit repo.
- only depends on the base devkitpro 3ds install - devkitarm, 3dstools

## Getting Started (C)

Install devkitpro-pacman, or setup your pacman with devkitpro packages, and set the necessary env vars,
following [these](https://devkitpro.org/wiki/Getting_Started) instructions,
then install the `3ds-dev` package via pacman.
This will install devkitARM and 3dstools (among other things such as libctru)

Install [xmake](https://xmake.io/)

Open [the 3dskit template repo](https://github.com/ys-3dskit/3dskit-template-c),
and click the green "use this template" button to create a homebrew app repo.

Clone the repo and run `xmake` in your terminal to build a 3dsx file which you can run in Citra or on a 3DS!

## Getting Started (D)

Follow the exact same instructions but with [the D template repo](https://github.com/ys-3dskit/3dskit-template-d).
