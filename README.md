# UninstallEdge

A PowerShell utility for uninstalling Microsoft Edge from Windows.

## About

UninstallEdge republishes a PowerShell script originally created by [ave9858](https://gist.github.com/ave9858/c3451d9f452389ac7607c99d45edecc6).

The original script identifies its license as **CC0 1.0 Universal**. This repository provides the script with additional documentation for users.

## Features

- PowerShell-based Windows utility.
- Automates the Microsoft Edge uninstallation process.
- Simple command-line execution.
- Original source and licensing information documented.

## Requirements

- A supported Windows installation.
- Windows PowerShell.
- Administrator privileges.
- A backup or Windows restore point is strongly recommended.

## Usage

1. Download `UninstallEdge.ps1` from this repository.
2. Review the script's source code before executing it.
3. Create a Windows restore point and back up important data.
4. Open PowerShell as Administrator.
5. Navigate to the directory containing the script.
6. Execute:

   ```powershell
   .\UninstallEdge.ps1
   ```

Follow any prompts or errors displayed by PowerShell.

## Important Safety Information

**This script modifies Windows registry settings and attempts to uninstall Microsoft Edge.**

Before running it:

- Understand the changes made by the script.
- Test it in a virtual machine before using it on your primary computer.
- Back up important files and create a restore point.
- Consider dependencies on Microsoft Edge and WebView2.
- Run it only on computers you own or are authorized to administer.

Removing Microsoft Edge may affect Windows features or applications that depend on Edge components. Results may vary depending on your Windows version and configuration.

Use this utility at your own risk.

## Original Source

The original script was published by [ave9858 on GitHub Gist](https://gist.github.com/ave9858/c3451d9f452389ac7607c99d45edecc6).

Original script copyright notice:

```text
SPDX-FileCopyrightText: Copyright (c) 2023 ave9858
SPDX-License-Identifier: CC0-1.0
```

The original copyright and SPDX notices should remain in the script.

## License

The original script identifies its license as **CC0 1.0 Universal**.

- [CC0 1.0 License Deed](https://creativecommons.org/publicdomain/zero/1.0/)
- [Official CC0 1.0 Legal Code](https://creativecommons.org/publicdomain/zero/1.0/legalcode.en)

For clarity, add a `LICENSE` file containing the appropriate CC0 1.0 license text. Ensure the repository's licensing information accurately reflects the original script and any additional contributions.

## Disclaimer

This is an independent community project. It is not affiliated with, endorsed by, or maintained by Microsoft or the original script author.

The software is provided "as is", without warranties or guarantees. Refer to the license for its applicable terms.

---

**Maintained by [iamsachinG](https://github.com/iamsachinG)**
