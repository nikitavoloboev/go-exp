# Contributing ♥️

Thank you for wanting to contribute!

Any type of contribution is welcome, not just code. You can help with:

- **Bugs / Features:** Share bug reports or make feature requests. Check [existing issues](../../issues) to avoid duplicates.
- **Code:** Run this project locally by reading instructions below. Take a look at open issues and see if something sparks your interest.
- **Docs:** Docs are the best contribution anyone can make to any project. Update docs if something is unclear or is missing.

## Run

The repo consists of go libraries and CLIs written in Go. Assuming all dependencies are installed (opening repo with [Go extension](https://github.com/golang/vscode-go) & [VSCode](https://code.visualstudio.com/download) should do it automatically).

Running `go run .` in folder with `main.go` will build & run the library/tool.

## Tips

[watchexec](https://github.com/watchexec/watchexec) is a nice tool for developing. Can make this alias:

`alias wg=watchexec --exts go "echo -- && go run ."`

When `wg` is then run, it will run `go run .` automatically whenever go file changes.

## Possible issues

If you run into issues that aren't yet fixed or documented but you have a solution for, please submit a PR! Otherwise open an issue. ♥️
