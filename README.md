# Symfony-cli-snap

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-white.svg)](https://snapcraft.io/symfony)

## Description

Unofficial snap package for the [Symfony CLI tool](https://github.com/symfony-cli/symfony-cli)

## Installation

```bash
sudo snap install --classic symfony
```

This package currently needs to be installed with classic confinement to be able to detect binaries such as php, pecl, pear, phpize...

## Usage

- Create new project:
  
  ```bash
  symfony new <project-name>
  ```
