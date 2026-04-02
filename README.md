<p align="center"> <img src="./images/logo.png" alt="Logo"> </p> <h1 align="center">zed-one-theme for vscode</h1>


![Number of GitHub Downloads badge](https://img.shields.io/github/downloads/lrisguan/zed-one-theme-vsc/total?color=pink&label=GitHub%20Downloads)

## Explanation
> [!Note]
> This repository is forked from [zed-one-theme-vs](https://github.com/arrrrny/zed-one-theme-vs). Under MIT license.
> Why I forked from him and developing it? Cause when I using it, I found there's no support for **markdown** format file.

## Feature
- **zed-like:**
A **zed-like** theme for vsc. Now support **light** theme and **dark** theme
- **markdown support:**
Support highlight markdown file.

## Quick start

### Using release
You can install this extension in [release](https://github.com/lrisguan/zed-one-theme-vsc/releases/download/0.1.0/zed-one-theme-0.1.0.vsix).
Open your vscode, type `ctrl+shift+p`, then input **install from vsix**. Now you just need to find
the place you downloaded `the vsix file` and click it. 

### Build on your own

- First clone this repo.
```bash
git clone https://github.com/lrisguan/zed-one-theme-vsc.git
```
- Then build the extension
> [!Tip]
> Ensure you have node.
> you can run below to test.
```bash
node --version
```
> If you not have one, install from the [official website](https://nodejs.org/) 

```bash
cd zed-one-theme-vsc
npx @vscode/vsce package
```
> [!Important]
> When running above command, you need to run your terminal as **Administrator**.

- After you run this, in your folder will generate a file ends with **.vsix**.

- In vsc, type `ctrl+shift+p`, then input below:
```markdown
install from vsix
```
- Then you should select the file ends with **.vsix** related above.

- Now you can enjoy the themes.

## Bug or others
You can add issues.
