# Downloading git on Windows and MACOS

## Downloading Git on Windows:

1. **Visit the Git website:**
   - Go to the [Git website](https://git-scm.com/) in your web browser.

2. **Download Git for Windows:**
   - Click on the "Download" button on the homepage.
   - Select the appropriate installer for your system architecture (32-bit or 64-bit).
   - Run the downloaded installer file (.exe).
   - Follow the installation wizard instructions, including choosing the installation directory and selecting components to install.

3. **Configure Git:**
   - During the installation process, you may be prompted to configure some settings such as your preferred text editor and terminal emulator.
   - You can also configure Git settings later using the following commands:

```bash
    git config --global user.name "Your Name"
    git config --global user.email "your.email@example.com"
    git config --global core.autocrlf true
```

4. **Verify Installation:**
   - Once the installation is complete, open a command prompt or Git Bash terminal and run the command `git --version` to verify that Git is installed correctly.

## Downloading Git on macOS:

1. **Install Xcode Command Line Tools (optional):**
   - If you haven't already installed Xcode Command Line Tools, open Terminal and run the command `xcode-select --install`.
   - Follow the prompts to install the tools.

2. **Install Homebrew (optional):**
   - If you prefer using Homebrew to manage packages, you can install Git via Homebrew.
   - Open Terminal and run the command `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`.

3. **Install Git with Homebrew (optional):**
   - Once Homebrew is installed, run the command `brew install git` in Terminal.

4. **Download Git from the Git website (alternative):**
   - Alternatively, you can download the Git installer for macOS from the [Git website](https://git-scm.com/).
   - Click on the "Download" button and follow the same steps as mentioned for Windows.

5. **Configure Git:**
   - After installation, you can configure Git settings using the following commands:
     ```
     git config --global user.name "Your Name"
     git config --global user.email "your.email@example.com"
     git config --global core.autocrlf input
     ```

6. **Verify Installation:**
   - After configuration, open Terminal and run the command `git --version` to verify that Git is installed correctly.
