 IT110-Project1-FileReview-

A technical analysis project focused on assessing and documenting a set of disorganized student submission files within a Linux environment. Although the original ZIP file was not modified directly in this repository, this project includes a script that represents the exact process used to reorganize and standardize the folder structure. This project uses command-line tools to:
- Analyze the file structure and naming conventions of student submissions
- Identify organizational issues and inconsistencies
- Implement a standardized folder structure for easy access and grading
- Document the process and provide recommendations for future submissions

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Bnerj/IT110-Project1-FileReview-.git
   ```
2. Run the primary script: 
   ```bash
   bash organize_submissions.sh/path/to/submissions
   ```
   This script takes a directory of unorganized submissions and outputs a standardized, cleaned structure.

## Review documentation

All observations, issues, and solutions are documented in:

report.md – Analysis and explanation of how the script solves the identified problems

## Requirements

- Linux (Ubuntu tested)
- Standard Unix command-line utilities (`ls`, `mv`, `awk`, etc.)

## Project Structure

- `organize_submissions.sh` - Main script to organize files
- `report.md` - Documentation of observed issues and solutions

## Author

- Bnerj

## License

MIT
