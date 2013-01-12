
# Github Checksums

This is YAST (Yet Another Simple Tool) for printing the checksums of your
Github project tarballs for specified tags (or more generally branches too).

This can be useful for updating Macports Portfiles for instance (or just
verifying checksums of course).

## Usage

To get the checksums for this project for example:

```
ghsum rodnaph/ghsum v0.1.0
```

This will then print the sha256 and rmd160 checksums required by Macports.

## Installation

ghsum can be installed straight from Macports.

```
sudo port install ghsum
```

