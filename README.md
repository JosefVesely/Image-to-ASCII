# <img src="img2ascii.png" width="350">

[![Made with C](https://img.shields.io/badge/Made%20with-C-blue.svg)](https://github.com/JosefVesely/Image-to-ASCII)
[![License: MIT](https://img.shields.io/badge/License-MIT-orange.svg)](https://github.com/JosefVesely/Image-to-ASCII/blob/main/LICENSE)
[![PRs: welcome](https://img.shields.io/badge/PRs:-welcome-limegreen.svg)](https://github.com/JosefVesely/Image-to-ASCII)
[![GitHub stars](https://img.shields.io/github/stars/JosefVesely/Image-to-ASCII.svg?style=social&label=Star)](https://github.com/JosefVesely/Image-to-ASCII)

A command-line tool for converting images to ASCII art


## Installation :cd:

```sh
# Clone the repository
git clone https://github.com/JosefVesely/Image-to-ASCII

# Enter the project directory
cd Image-to-ASCII

# Compile the program using Make
make
```


## Usage :clipboard:

```c
Usage: img2ascii [options] -i <FILE> [-o <FILE>]

A command-line tool for converting images to ASCII art

Options:
    -i, --input  <FILE>     Path of the input image file (required)
    -o, --output <FILE>     Path of the output file
    -w, --width  <NUMBER>   Width of the output
    -c, --chars  <STRING>   Characters to be used for the ASCII image
    -p, --print             Print the output to the console
    -r, --reverse           Reverse the string of characters
```


## Examples :star2:

|                     Input                     |                                 Output                                 |
|-----------------------------------------------|------------------------------------------------------------------------|
| <img src="images/c.png" width="300">          | <img src="examples/ascii-c.png" width="500">                           |
|                                               | `img2ascii -i images/c.png -w 40 -p`                                   |
| <img src="images/monroe.jpg" width="300">     | <img src="examples/ascii-monroe.png" width="500">                      |
|                                               | `img2ascii -i images/monroe.jpg -w 35 -p -r`                           |
| <img src="images/pink_floyd.jpg" width="300"> | <img src="examples/ascii-pink_floyd.png" width="500">                  |
|                                               | `img2ascii -i images/pink_floyd.jpg -w 80 -p -r`                       |
| <img src="images/pepsi.png" width="300">      | <img src="examples/ascii-pepsi.png" width="500">                       |
|                                               | `img2ascii -i images/pepsi.png -w 35 -p -r`                            |
| <img src="images/aperture.jpg" width="300">   | <img src="examples/ascii-aperture.png" width="500">                    |
|                                               | `img2ascii -i images/aperture.jpg -w 50 -p`                            |


## TODO :heavy_check_mark:

- [ ] Add option for colored output
- [ ] ~~Name the output files with input filename and date (e.g. monroe_08-18-2023.txt)~~
- [X] Name the output files with input filename (e.g. monroe.txt)
- [ ] Create a release


## Contributing :handshake:

Contributions are welcome! If you have any improvements or bug fixes, feel free to submit a pull request


## License :page_facing_up:

This project is licensed under the MIT License - see the [LICENSE](https://github.com/JosefVesely/Image-to-ASCII/blob/main/LICENSE) file for details