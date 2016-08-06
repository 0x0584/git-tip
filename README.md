# gtip

> CLI that gives a random git-tip.

The git-tips [JSON file](https://github.com/git-tips/tips/blob/master/tips.json) is taken from this awesome project - [git-tips](https://github.com/git-tips/tips)

## Install

```
$ npm install --global gtip
```

## Usage

```
  Usage
      $ gtip [options]
  Options
      --help    Provides usage help (Shows the current page)
      --all     Gives all the git tips
      <keyword> Gives the git tips consisting of the keyword
  Examples
      $ gtip bypass

      1. Bypass pre-commit and commit-msg githooks
      => git commit --no-verify

      $ gtip

      Git Tip of the Terminal
      -------------------------
      Saving current state of tracked files without commiting
      => git stash
```

## License
MIT © [Niraj Pandkar](https://github.com/nirajpandkar)