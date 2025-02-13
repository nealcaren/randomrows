# randomrows

A simple command-line tool to display the header and random rows from a CSV or text file.

## Installation

```bash
brew tap nealcaren/tools
brew install randomrows
```

## Usage

```bash
randomrows -f <input_file> [-n <number_of_rows>] [-s <save_file>] [-h]
```

Options:
- `-f` Input file (required)
- `-n` Number of random rows (default: 5)
- `-s` Save output to CSV file
- `-h` Display help message

## Examples

```bash
# Display 10 random rows from data.csv
randomrows -f data.csv -n 10

# Save 5 random rows to sample.csv
randomrows -f data.csv -s sample.csv

# Display 15 random rows and save to output.csv
randomrows -f data.csv -n 15 -s output.csv
```
