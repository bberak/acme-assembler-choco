# ACME Assembler - Chocolatey Package

This repo contains the choco package artefacts for install the [ACME Assembler](https://sourceforge.net/projects/acme-crossass/) on your Windows machine

## Prequisites

- [Chocolatey](https://chocolatey.org/)

## Installing Package

Build the .nupkg:

```
git clone https://github.com/bberak/acme-assembler-choco.git
cd acme-assembler-choco
choco pack
```

Intall the .nupkg using choco:

```
choco install acme-assembler.0.96.4.0.nupkg
```

You can now run ACME from the commandline:

```
acme
```

## Uninstalling Package

To remove, simply run:

```
choco uninstall acme-assembler
```