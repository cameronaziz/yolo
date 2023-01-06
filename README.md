# yolo

## Usage

`git yolo`

## The Alias

The alias runs this command:

```sh
git add -A && \
  git commit -am "`curl -s http://whatthecommit.com/index.txt `" && \
  git push -f origin HEAD
```

## Installation

```sh
curl -L https://raw.githubusercontent.com/cameronaziz/yolo/master/install.sh | sudo bash
```
