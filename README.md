# untar
Unpack tar archives with various compression algorithms (gz, bzip2 etc.)

## Usage
Quite simple:

    untar $PATH_TO_ARCHIVE

It'll extract your tar archive to the current directory.
Currently `untar` supports tar archive compressed with the GZIP compression algorithm, more to come.

## Disclaimer
I'm new to Rust, to this code is far from being Rusty-perfect. If you got severel improvements or suggestions just open
up a PR, I'm happy about it!

Besides that `untar` is still a work in progress. More compression algorithms (bzip2, zlib) are yet to come as well as
some more conventient functionallity.

## License
This project is licensed under the terms and conditions of the MIT license; see LICENSE for more details.
