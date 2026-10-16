# Ashling RiscFree™ for Arm & RISC-V Development: issues and feedback

This is the public issue tracker for the **Ashling RiscFree™ for Arm & RISC-V Development** extension for Visual Studio Code.

The extension's source code is not public. This repository contains no source. It holds:

- the issue tracker, for bug reports and feature requests;
- the screenshots shown in the extension's Marketplace README.

## Get the extension

- **Install**: search for **Ashling RiscFree** in the Extensions view in VS Code, or visit the [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=Ashling.riscfree).
- **Documentation**: [docs.ashling.com/vscode](https://docs.ashling.com/vscode/)

## Report a bug or request a feature

1. Search the [existing issues](https://github.com/AshlingMicrosystems/vscode-extension/issues) first, in case it has already been reported.
2. Open a [new issue](https://github.com/AshlingMicrosystems/vscode-extension/issues/new/choose) and choose **Bug report** or **Feature request**.

Issues are public. Don't include license keys, customer names, confidential source code or private file paths. If you need to share anything confidential, email [support@ashling.com](mailto:support@ashling.com) instead.

## Get support

For technical support, licensing, probes or anything you'd rather not post in public, contact [support@ashling.com](mailto:support@ashling.com).

## Report a security vulnerability

Don't report security vulnerabilities in public issues. See [SECURITY.md](SECURITY.md).

## Screenshots

The `images/` folder holds the screenshots for the extension's Marketplace README. Each extension release links to the images through a git tag named after its version, such as `v26.4.0`, so published READMEs keep showing the right images when they change later.

To add or update screenshots for a release:

1. Commit the new or changed images to `main`.
2. Tag that commit with the extension version and push the tag:

   ```sh
   git tag -a v<version> -m "Screenshots for RiscFree <version>"
   git push origin v<version>
   ```

3. In the extension's `README.md`, point the image links at the tag:

   ```text
   https://raw.githubusercontent.com/AshlingMicrosystems/vscode-extension/v<version>/images/<file>.png
   ```

Don't move or delete a tag once a release that uses it has been published.

## License

Copyright © Ashling Microsystems Ltd. All rights reserved. See [LICENSE](LICENSE).
