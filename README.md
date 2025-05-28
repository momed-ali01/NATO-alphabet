# NATO Phonetic Alphabet Converter

A Python application that converts regular text into the NATO phonetic alphabet. This tool helps users learn and practice the NATO phonetic alphabet, which is used in military, aviation, and telecommunications to ensure clear communication of letters and numbers.

## Features

- Converts any word into its NATO phonetic alphabet equivalent
- Case-insensitive input handling
- Error handling for non-alphabetic characters
- Interactive command-line interface
- Uses pandas for efficient data handling
- CSV-based NATO alphabet reference

## Requirements

- Python 3.x
- pandas library

## Installation

1. Clone this repository:

```bash
git clone https://github.com/momed-ali01/NATO-alphabet.git
cd NATO-alphabet
```

2. Install the required dependencies:

```bash
pip install pandas
```

## Usage

Run the application:

```bash
python main.py
```

### How to Use

1. When prompted, enter any word you want to convert
2. The program will display the NATO phonetic alphabet equivalent for each letter
3. If you enter non-alphabetic characters, you'll be prompted to try again

### Example

Input: "Hello"
Output: ['Hotel', 'Echo', 'Lima', 'Lima', 'Oscar']

## The NATO Phonetic Alphabet

The NATO phonetic alphabet is a spelling alphabet used by pilots, air traffic controllers, and military personnel to communicate letters and numbers clearly over radio or telephone. Each letter of the alphabet is assigned a specific word to avoid confusion between similar-sounding letters.

## Contributing

Feel free to submit issues and enhancement requests! Some potential improvements could be:

- Adding a graphical user interface
- Supporting number conversion
- Adding pronunciation guides
- Implementing batch processing for multiple words

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Future Enhancements

- Add support for numbers and special characters
- Implement a GUI version
- Add pronunciation audio files
- Include a learning mode with quizzes
- Add support for multiple languages
