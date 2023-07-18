# UserForge
UserForge is a simple Python-based username generator tool. It creates username combinations based on the input parameters such as first name, last name, middle name, nickname, and year. This tool is useful when you need a list of potential usernames for a person for tasks such as brute forcing during penetration tests.

## Requirements
Python 3.6 or higher is required to run UserForge.

## Installation
1. Clone this repository to your local machine.
```bash
git clone https://github.com/yourusername/userforge.git
```
2. Navigate to the project directory.
```bash
cd userforge
```
3. Run the script using Python.
```bash
python3 userforge.py
```
## Usage
The UserForge tool accepts the following command line arguments:

-f, --first: First name (required)
-l, --last: Last name (required)
-m, --middle: Middle name (optional)
-n, --nickname: Nickname (optional)
-y, --year: Year (optional)
-o, --output: Output filename (optional, default is usernames.txt)
Example usage:
```bash
python3 userforge.py -f John -l Smith -m Ross -n Johnny -y 1992
```
This will generate username combinations based on the input names and year, and will output to usernames.txt.

## Output
The output file (usernames.txt by default) will contain a list of generated usernames, one per line. The usernames are created based on various combinations of the input names and initials, with or without separators ('_', '-', or '.') and optional year suffixes.
