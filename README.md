### 🎉 Welcome to the WebP Conversion Magic README! 🎨✨

![screenshot](webp-conversion-magic.png)

This tool is your go-to solution for converting images to WebP format with ease and efficiency. Say goodbye to bulky image files and hello to lightning-fast loading times! 🚀

### Table of Contents

- [Full Descriptions](#full-descriptions)
- [Best Use Cases](#best-use-cases)
- [Installation](#installation)
  - [Requirements](#requirements)
  - [Windows](#installation-steps-on-windows)
  - [MacOSX](#installation-steps-on-macosx)
  - [Linux](#installation-steps-on-linux)
- [Usage](#usage)
- [Parameters](#parameters)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

### Full Descriptions

This tool allows you to effortlessly convert your images to the highly optimized WebP format, reducing file sizes without compromising on quality. Whether you're a web developer, digital marketer, or content creator, this tool is your secret weapon for supercharging your website's performance! 💪🌟

### Best Use Cases

- **Web Development**: Optimize your website's images for faster loading times and improved user experience.
- **Digital Marketing**: Enhance your online campaigns with optimized images that load quickly across all devices.
- **Content Creation**: Streamline your content creation process by converting images to WebP format in just a few clicks.

### Installation

#### Requirements

Before using this tool, make sure you have the following dependencies installed:

- [cwebp](https://developers.google.com/speed/webp/download): Command-line tool for converting images to WebP format.
- [ImageMagick](https://imagemagick.org/): Suite of command-line tools for image manipulation.

#### Installation Steps on Windows

1. Download and install the latest version of cwebp for Windows.
2. Download and install ImageMagick for Windows.
3. Clone or download this repository to your local machine.
4. Open Command Prompt and navigate to the directory containing the script.
5. Run the script using the command `./webp-conversion.sh`.

#### Installation Steps on MacOSX

1. Install Homebrew by following the instructions on the official website.
2. Install cwebp by running `brew install webp`.
3. Install ImageMagick by running `brew install imagemagick`.
4. Clone or download this repository to your local machine.
5. Open Terminal and navigate to the directory containing the script.
6. Run the script using the command `./webp-conversion.sh`.

#### Installation Steps on Linux

1. Install cwebp using your package manager. For example, on Ubuntu, you can run `sudo apt-get install webp`.
2. Install ImageMagick using your package manager. For example, on Ubuntu, you can run `sudo apt-get install imagemagick`.
3. Clone or download this repository to your local machine.
4. Open Terminal and navigate to the directory containing the script.
5. Run the script using the command `./webp-conversion.sh`.

### Usage

Simply run the script with the desired configuration parameters to start converting your images to WebP format. Customize the quality, resizing options, and more to meet your specific needs.

### Parameters

- `quality`: Set the quality parameter (0-100, where 100 is the highest quality).
- `width` and `height`: Set the desired width and height for the output images (0 for no resizing).
- `alpha_compression`: Alpha compression option (0 for compression, 1 for no compression).
- `preserve_metadata`: Preserve metadata option (all for preserving all metadata, none for stripping all metadata).
- `effort`: Effort level (0 to 6, where higher values require more processing time).
- `overwrite`: Overwrite existing output files (0 for no overwrite, 1 for overwrite).

### Examples

```bash
./webp-conversion.sh
```

### Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request to suggest improvements or new features.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 📜✨
