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

This will then print the sha256 and rmd160 checksums required by Macports like this...

```
sha256: 863ce994a8a9a276f3ea8a6a395b33015540cccf08c8e419223aa8253ed42eb2
rmd160: 8135a086a7ba075d5ce3596caaa46cd21705bb64
```

## Installation

ghsum can be installed straight from Macports.

```
sudo port install ghsum
```

