# Huffman Coding Project

This project implements Huffman coding, a widely-used algorithm for lossless data compression. Huffman coding assigns variable-length codes to input characters, with shorter codes assigned to more frequent characters, resulting in efficient compression of data.

## Files

- `compressedFile.huf`: The compressed file generated after applying Huffman coding to the input file.
- `decode.cpp`: C++ source code for decoding the compressed file and retrieving the original data.
- `encode.cpp`: C++ source code for encoding an input file using Huffman coding and generating the compressed file.
- `huffman.cpp`: Implementation of the Huffman coding algorithm.
- `huffman.hpp`: Header file containing declarations of classes and functions used in the Huffman coding implementation.
- `inputFile.txt`: Sample input file used for compression.
- `main`: Executable file or script for running the Huffman coding project.
- `outputFile.txt`: Sample output file containing the decompressed data.

## Usage

1. **Encoding:**
   - Compile and run `encode.cpp` to compress an input file using Huffman coding.
   - Provide the input file path as an argument to the executable.
   - The compressed file (`compressedFile.huf`) will be generated in the same directory.

2. **Decoding:**
   - Compile and run `decode.cpp` to decompress the compressed file and retrieve the original data.
   - Ensure that the compressed file (`compressedFile.huf`) is present in the same directory as the executable.
   - The decompressed data will be written to `outputFile.txt`.

## How to Run

1. Clone or download the project repository to your local machine.
2. Compile the source files using a C++ compiler (e.g., g++).
3. Execute the generated executables to perform compression and decompression operations.

## Dependencies

This project does not have any external dependencies. It can be compiled and run using a standard C++ compiler.

## Contribution

Contributions to this project are welcome! If you find any bugs or have suggestions for improvements, feel free to open an issue or create a pull request.

