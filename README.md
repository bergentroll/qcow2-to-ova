# Qcow2 to OVA converter script

## Introduction

This script helps to convert a GNU/Linux Qcow2 cloud image into an OVA file.

The OVF file included into this script was taken from an Ubuntu OVA file.

## Dependencies

This script depends on `qemu-img`.

## Usage

Create a new directory:

```bash
mkdir qcow2ova
cd qcow2ova
```

Download the script, e.g.:

```bash
wget https://github.com/bergentroll/qcow2-to-ova/qcow2-to-ova.sh
```

Put a Qcow2 image into the directory and edit variables on top of the script:

```bash
mv PATH_TO_IMAGE ./
vim qcow2-to-ova.sh
```

Change permissions:

```bash
chmod a+x qcow2-to-ova.sh
```

Execute the script:

```bash
./qcow2-to-ova.sh
```

## License

[GNU General Public License version 2 (GPLv2)](https://github.com/burbuja/debian-ova-creator/blob/master/LICENSE) or later
