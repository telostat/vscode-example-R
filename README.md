# R with Visual Studio Code

This repository includes instructions and examples to work on R using Visual
Studio Code (VS Code).

## Quickstart

Open a terminal. Then, clone this repository:

```
git clone git@github.com:telostat/vscode-example-R.git
```

Once it is cloned, change to the root directory of the repository:

```
cd vscode-example-R
```

Finally, run VS Code on the root directory (note the `.` after `code` command):

```
code .
```

Once VS Code has started, you may be prompted to install recommended extensions
in case that you have not installed them yet.

See [`.vscode/extensions.json`](.vscode/extensions.json) for recommended
extensions (not only for R). One of them is commented out: *Emacs Keybindings*.
Enable it if you are used to Emacs keybindings.

## Files of Interest

1. Example RMarkdown file: [`./document.Rmd`](./document.Rmd)
2. *Library* file: [`./library.R`](./library.R)
3. *Program* file: [`./execute.R`](./execute.R)
