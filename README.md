# AWAP 2024 Game Engine

## Installation
`pip install compress_json pygame`

## Running Game Engine

To run the game engine, run the command:

`python run_game.py -b blueBotFile -r redBotFile -m mapFile --render`

### Required arguments:

`-m` -> A path to a map file. (e.g. `maps/spiral.awap24m`)

`-b` -> A path to a bot (blue team). (e.g. `bots/random_bot.py`)

`-r` -> A path to a bot (red team).

OR

`-c` -> The path to a .json file that specifies the map, red bot, and blue bot (e.g. `config.json`).

### Optional arguments:

`--render` -> Display the game as it's being played out.

### Example commands:
`python run_game.py -b bots/random_bot.py -r bots/nothing_bot.py -m maps/spiral.awap24m --render`

`python run_game.py -c config.json --render`
