# csv2roammd

A simple python script to convert CSV data into Roam Research's markdown table format.
There are no non-standard dependencies, and no installation is required.

## Installation

1. Clone this repo, or just copy the `csv2roammd` file.
2. Optional: Put the file somewhere included in your `PATH` environment variable. 
3. Optional:`chmod +x csv2roammd`.

## Usage

csv2roammd runs on stdin and prints to stdout.

Creating a .md file:
```
cat input.csv | csv2roammd > output.md
```

Copying to you macOS clipboard:
```
cat input.csv | csv2roammd | pbcopy
```

Using the script if you don't add it to your environment's `PATH`:
```
cat input.csv | python ./csv2roammd > output.md
```

