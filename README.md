cpdisks
=======

by Rémino Rem <https://remino.net/>

Copy several disks one by one in a single directory.

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Installation

```sh
# macOS
brew tap remino/remino
brew install cpdisks

# Other platforms
curl -sL https://raw.githubusercontent.com/remino/cpdisks/master/cpdisks > /usr/local/bin/cpdisks
```

## Usage

```
cpdisks 1.0.0

USAGE: cpdisks [<options>] <source disk> <destination dir>

Copy several disks one by one in a single directory.

This will copy the contents of the disk to the destination directory under a
subdirectory named after the disk. The disk will be ejected after copying and
the process will wait for the next disk to be inserted.

To end the process, press Ctrl+C.

Works best on macOS. On other platforms, the disk must be ejected manually.

OPTIONS:

	-h        Show this help screen.
	-v        Show script name and version number.

```

## License

See [LICENSE](LICENSE.txt).
