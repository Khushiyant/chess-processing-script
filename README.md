# Chess ML Data Processing Script

It is [*.pgn]() processing script for creating the label for good move

## Installation

Use the package clone cmd [git clone]() to clone script.

```powershell
git install https://github.com/Khushiyant/chess-processing-script.git
```

## Usage

```python
from labelling import process_game_data 
import os

for dirname, _, filenames in os.walk('path_to_player_folder'):
    for filename in filenames:
        process_game_data(dirname, filename)
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[GPL v3](https://www.gnu.org/licenses/gpl-3.0.en.html)
