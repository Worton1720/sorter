# File Organizer

File Organizer is a Python script that helps you organize your files into categorized folders based on their file extensions. It's a handy tool to keep your directories neat and tidy.

## Features

- Organize files into categories such as video, code, audio, image, etc.
- Customizable file extension categories.
- Handles file renaming to prevent conflicts.
- Removes empty folders after organizing files.

## Installation

1. Clone the repository:

```
git clone https://github.com/your_username/file-organizer.git
```

2. Install dependencies:

```
pip install -r requirements.txt
```

## Usage

1. Navigate to the project directory:

```
cd file-organizer
```

2. Run the main script:

```
python main.py
```

3. Enter the directory path you want to organize or press Enter to use the default Downloads directory.

4. The script will organize files in the specified directory into categorized folders.

5. Optionally, continue organizing files in other directories as needed.

## Configuration

You can customize file extension categories by modifying the `extensions` dictionary in the `main.py` file.

## Dependencies

- Python 3.x
- Colorama

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
