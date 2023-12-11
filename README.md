# Journey

Journey is a straightforward CLI journalling program that allows you to create, manage, and access daily entries with a text-file–based system, simplifying your journalling experience.

## Installation

To start using Journey, follow these steps:

1. Download or clone the Journey repository.
2. Move the `journey` script to a directory included in your system's `PATH`, or alternatively, add the current location to your `PATH` variable.

To add Journey to your `PATH` temporarily (for the current session):

```bash
export PATH="$PATH:/path/to/journey/directory"
```

To make this change permanent, add the above line to your shell's configuration file, e.g. `.bashrc`, `.zshrc`.

Once Journey is in your `PATH`, you can use it from any directory on your system by simply typing `journey <command>` in your terminal.

## Usage

Journey supports the following commands:

- `journey init`: Initialises the Journey base folder.
- `journey new`: Creates a new journal entry for the current day and opens it in the default editor.
- `journey show`: Displays the contents of the current day's journal entry using the `less`` pager.
- `journey write`: Opens the current day's journal entry in the default editor for writing or editing.
- `journey vim`: Opens the current day's journal entry in Vim for writing or editing.
- `journey nano`: Opens the current day's journal entry in the Nano editor for writing or editing.
- `journey *`: If an recognised command is provided, the script will display a default message.

## Configuration

Users can customise their default editor by editing the `EDITOR` variable in the script.

## License

This software is released under the EU Public Licence v. 2.0.

## Bugs and Support

For any bugs, issues, or support, please contact `noah@noahdominic.com`. We welcome your feedback to enhance your Journey experience.

Happy journalling!
