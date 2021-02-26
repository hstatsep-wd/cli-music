# Command Line Interface Practice: Music

## Task 0: Observe the current file structure

```
cli-music
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

## Task 1: Modifying the File Tree

Using ONLY the command line, change your file tree until it matches what you see below:

```
cli-music
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

If you made a mistake, you can undo your changes with the following command:

`git restore .`

NOTE: this will not delete any folders you created (or renamed)

## Task 2: Push your work!

`cd` to the top level directory of _this_ repository (i.e. `cli-music...`)

Copy/paste the following commands to send your work to Github:
```bash
history >> commands.txt
git add .
git commit -m "update repo"
git push
```

NOTE: make sure you press <kbd>ENTER</kbd> after that last command!