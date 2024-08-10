<img src="img2ascii.png">

[![Made with C](https://img.shields.io/badge/-Made%20with%20C-5C6BC0?logo=C)](https://github.com/JosefVesely/Image-to-ASCII)
[![MIT License](https://img.shields.io/badge/MIT_License-09A44D)](https://github.com/JosefVesely/Image-to-ASCII/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/JosefVesely/Image-to-ASCII.svg?label=Stars)](#Star)

A command-line tool for converting images to ASCII art

---

## 🛠️ Installation

```sh
# Clone the repository
git clone https://github.com/JosefVesely/Image-to-ASCII

# Navigate to the project directory
cd Image-to-ASCII

# Compile the program using Make
make
```

## 🚀 Usage

Run using the following syntax:

```md
img2ascii [options] -i <FILE> [-o <FILE>]
```

### Options:

| Short | Long      | Argument | Description                                     |
|-------|-----------|----------|-------------------------------------------------|
| -i    | --input   | *File*   | Path of the input image file ***(required)***   |
| -o    | --output  | *File*   | Path of the output file                         |
| -w    | --width   | *Number* | Width of the output image                       |
| -c    | --chars   | *String* | Characters to be used for the ASCII image       |
| -p    | --print   |          | Print the output to the console                 |
| -r    | --reverse |          | Reverse the string of characters                |

## 🧩 Examples

| Input                                            | Output                                           |
|--------------------------------------------------|--------------------------------------------------|
| <img src="images/c.png" width="300">             | <img src="examples/ascii-c.png" width="500">      |
| `img2ascii -i images/c.png -w 40 -p`             |                                                  |
| <img src="images/monroe.jpg" width="300">        | <img src="examples/ascii-monroe.png" width="500"> |
| `img2ascii -i images/monroe.jpg -w 35 -p -r`     |                                                  |
| <img src="images/pink_floyd.jpg" width="300">    | <img src="examples/ascii-pink_floyd.png" width="500"> |
| `img2ascii -i images/pink_floyd.jpg -w 80 -p -r` |                                                  |
| <img src="images/pepsi.png" width="300">         | <img src="examples/ascii-pepsi.png" width="500">  |
| `img2ascii -i images/pepsi.png -w 35 -p -r`      |                                                  |
| <img src="images/aperture.jpg" width="300">      | <img src="examples/ascii-aperture.png" width="500"> |
| `img2ascii -i images/aperture.jpg -w 50 -p`      |                                                  |

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/JosefVesely/Image-to-ASCII/blob/main/LICENSE) file for details
