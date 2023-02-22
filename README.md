***If you want to contribute to the project, you can fork the project and submit a pull request. If you want to contribute to the project, you can fork the project and submit a pull request.***

# Installation
## For windows Users
### Windows 10 or above
you can use windows native package manager `winget` to install `git` and `vscode`.
```powershell
winget install -e --id "Git.Git"
wnget install -e --id "Microsoft.VisualStudioCode"
```

### Windows 7 or 8

Since windows 7 and 8 don't have a native package manager, you can download the installer from the official website.

## For Linux Users

### Ubuntu and Debian

```bash
sudo apt install git
sudo snap install --classic code
```

### Fedora

```bash
sudo dnf install git
sduo dnf install code
```

# Usage

after installing `git` and `vscode`, you can clone the project and open it in vscode.
```powershell
git clone https://github.com/Bengerthelorf/Markdown.git
```

Don't forget to set your own username and email in git.
```powershell
git config --global user.name "your name"
git config --global user.email "your email"
```

than open the project in vscode, and install the recommended extensions: `markdown all in one`, `Markdown Preview Enhanced`, `Markdown preview Mermaid support` and `Markmap`

After that, you can edit the markdown files in the `Markdown` folder, and use the `markdown preview enhanced` to preview the changes, which shall be able to view simply by using `ctrl+shift+v`.

You can use the `git` shortcut on the left sidebar of vscode to commit your changes.