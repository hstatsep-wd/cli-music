# Command Line Interface Practice: Music

## Before you begin: observe the current file tree

```
cli-music-yourUsername
|-- country
|   |-- taylor-swift.txt
|-- hip-hop
|   |-- east-coast
|   |   |-- grandmaster-flash.txt
|   |   |-- public-enemy.txt
|   |-- west-coast
|   |   |-- dr-dre.txt
|   |   |-- ice-cube.txt
|-- rap
|   |-- eminem.txt
|   |-- jay-z.txt
|   |-- notorious-big.txt
|-- rock
|   |-- blink-182.txt
|   |-- nirvana.txt
|-- README.md
```

## Task: Modifying the File Tree

Using ONLY the command line, change your file tree until it matches what you see below:

```
cli-music-yourUsername
|-- pop
|   |-- taylor-swift.txt
|-- punk-rock
|   |-- blink-182.txt
|-- rap
|   |-- alive
|   |   |-- eminem.txt
|   |   |-- jay-z.txt
|   |-- dead
|   |   |-- notorious-b-i-g.txt
|-- README.md
```

If you made a mistake, you can undo (almost) all of your changes by making sure you are the top-level directory of _this_ repo (i.e. `cli-music...`) and doing the following command:

`git restore .`

NOTE: this will not delete any folders you created (or renamed)

## Pushing your work!

`cd` to the top level directory of _this_ repo (i.e. `cli-music...`)

Copy/paste the following commands to send your work to Github:
```
history >> commands.txt
git add .
git commit -m "update repo"
git push

```

NOTE: make sure you press <kbd>ENTER</kbd> after that last command!
