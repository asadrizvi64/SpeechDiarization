# Speech Diarization Project

This project is designed to perform speaker diarization on a given audio file, separating out individual speaker segments and labeling them with speaker IDs. 

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)

## Installation
1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`

## Usage
1. Navigate to the root directory of the project.
2. Run the command `python diarization.py <path_to_audio_file>` to perform speaker diarization on the given audio file.
3. The output will be saved as a text file named `output.txt` in the same directory as the input audio file.

## Example
$ python diarization.py path/to/audio.wav

This will generate a file `output.txt` containing the speaker IDs and corresponding timestamps for each speaker segment in the input audio file.

## Contributing
We welcome contributions from the community! To contribute to this project, please follow these steps:
1. Fork this repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them to your branch.
4. Submit a pull request to the `main` branch of this repository.

## License
This project is licensed under the [MIT License](LICENSE).
