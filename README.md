<div align="center">
<pre align="center">
<h2 align="center">
;; Python-Game-of-Life ;;
</h2>
<h4 align="center">Conway's Game Of Life implementation in python</h4>
</pre>
</div>

## Installation
```sh
# clone git repo
git clone https://github.com/ahmed-bin-nasser/py-game-of-life.git
# goto repo folder
cd py-game-of-life
# install locally via pip
pip install -e .
```

## Usage
```sh
py-game-of-life -h
```

```text
usage: py-game-of-life [-h] [--version] [-p {Blinker,Toad,Beacon,Pulsar,Penta Decathlon,Glider,Glider Gun,Bunnies}] [-a] [-v {CursesView}]
                       [-g NUM_GENERATIONS] [-f FRAMES_PER_SECOND]

Conway's Game Of Life implementation in python

options:
  -h, --help            show this help message and exit
  --version             show program's version number and exit
  -p {Blinker,Toad,Beacon,Pulsar,Penta Decathlon,Glider,Glider Gun,Bunnies}, --pattern {Blinker,Toad,Beacon,Pulsar,Penta Decathlon,Glider,Glider Gun,Bunnies}
                        take a pattern for the Game of Life (default: Blinker)
  -a, --all             show all available patterns in a sequence
  -v {CursesView}, --view {CursesView}
                        display the life grid in a specific view (default: CursesView)
  -g NUM_GENERATIONS, --gen NUM_GENERATIONS
                        number of generations (default: 10)
  -f FRAMES_PER_SECOND, --fps FRAMES_PER_SECOND
                        frames per second (default: 7)
```

## Run Tests

```sh
pytest -v
```
