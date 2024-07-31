# MP3-to-Audiobook-Converter

A Python script to convert MP3 files to audiobook formats (M4B and AAX).

## Description

This project provides a simple command-line tool to convert MP3 files into popular audiobook formats. It's useful for creating audiobooks from MP3 files or converting existing audiobooks to different formats.

## Features

- Converts MP3 files to M4B or AAX formats
- Sets appropriate metadata for audiobook files
- Easy-to-use command-line interface

## Requirements

- Python 3.6+
- FFmpeg (must be installed separately)
- Python libraries: pydub, mutagen

## Installation

1. Clone this repository: `git clone https://github.com/yourusername/MP3-to-Audiobook-Converter.git` 
`cd MP3-to-Audiobook-Converter` 
3. Install the required Python libraries: `pip install -r requirements.txt` 

## Usage

To use the MP3-to-Audiobook-Converter, run the script from the command line with the following syntax:
`python mp3_to_audiobook_converter.py <input_file> <output_format>` 

Parameters:
- `<input_file>`: The path to your MP3 file
- `<output_format>`: The desired output format (either 'm4b' or 'aax')

Example:
`python mp3_to_audiobook_converter.py path/to/your/input.mp3 m4b`

This command will convert the MP3 file located at `path/to/your/input.mp3` to the M4B audiobook format.

For AAX format, you would use:
`python mp3_to_audiobook_converter.py path/to/your/input.mp3 aax`

The converted file will be saved in the same directory as the input file, with the same name but a different extension.

This usage pattern clearly shows what the script does and how to use it. The input file path and desired output format are specified directly in the command, making it easy to convert different files to different formats as needed.

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check [issues page](https://github.com/yourusername/MP3-to-Audiobook-Converter/issues) if you want to contribute.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
