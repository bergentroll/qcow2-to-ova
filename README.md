# debian-ova-creator

## Introduction

This script helps you to download a Debian cloud image and to convert it into an OVA file.

The OVF file included into this script was taken from an Ubuntu OVA file.

## Dependencies

This script depends of wget and qemu-img packages that you may install using the following command:

```sh
sudo apt install -y wget qemu-img
```

## Usage

Create a new directory:

```sh
mkdir debian-ova
```

Change directory:

```sh
cd debian-ova
```

Download this script:

```sh
wget https://raw.githubusercontent.com/burbuja/debian-ova-creator/master/debian-ova-creator.sh
```

Edit it:

```sh
nano debian-ova-creator.sh
```

Change the permissions:

```sh
chmod +x debian-ova-creator.sh
```

Execute it:

```sh
./debian-ova-creator.sh
```

## License

[GNU General Public License version 2 (GPLv2)](https://github.com/burbuja/debian-ova-creator/blob/master/LICENSE) or later
