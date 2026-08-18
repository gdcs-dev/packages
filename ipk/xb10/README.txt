# OPKG Repository

This is an OPKG repository for aarch64 packages.

## Usage

Add this repository to your OPKG configuration:

1. Edit /etc/opkg/customfeeds.conf (or similar):
   ```
   src/gz custom-packages https://stepherg.github.io/package-workflows/opkg
   ```

2. Update package list:
   ```
   opkg update
   ```

3. Install packages:
   ```
   opkg install <package-name>
   ```

## Repository Structure

- *.ipk - Package files
- Packages - Package index (uncompressed)
- Packages.gz - Package index (compressed)
- Packages.sig - Package signature (for verification)

## Architecture

This repository contains packages for: aarch64
