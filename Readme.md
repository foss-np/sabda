## How to compile
```bash
$ mkdir sabda-base
$ cd sabda-base
$ git clone https://github.com/foss-np/sabda master
$ mkdir src gh-pages
$ cd master
$ git worktree add ../gh-pages gh-pages
$ git worktree add ../src src
$ cd ../src
$ go run src/main.go src/PageFactory.go
```