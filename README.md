# FileZipper

## Overview
This project implements a Huffman coding tool to compress and decompress text files efficiently. The tool uses Huffman coding to reduce file sizes while maintaining data integrity.

## Features
- **Efficient Compression:** Reduces file sizes using Huffman coding.
- **Fast Decompression:** Quickly restores original files with minimal data loss.
- **Advanced Algorithms:** Utilizes priority queues and optimal tree construction techniques.
- **C++ Implementation:** Demonstrates proficiency in C++ with advanced algorithms and memory management.

## File Structure
- `encode.cpp`: Main file to execute the Huffman compression.
- `decode.cpp`: Main file to execute the Huffman decompression.
- `huffman.cpp`: Contains the implementation of the Huffman coding algorithm.
- `huffman.hpp`: Header file defining the Huffman tree structure and methods.

## Getting Started

### Prerequisites
- **C++ Compiler:** Ensure you have g++ installed on your system.

### Compilation and Execution
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/DeepAryanSharma/FileZipper-tool.git
   cd huffman-compression-tool
   
2. **Compile the Code:**
    ```sh
    g++ -o huffman_compressor encode.cpp huffman.cpp
    g++ -o huffman_decompressor decode.cpp huffman.cpp

3. **Run the Program:**
    ```sh
    ./huffman_compressor input.txt compressed.huf
    ./huffman_decompressor compressed.huf output.txt

## Usage
Place the input file input.txt in the same directory as the executable. Run the compression program to generate the compressed file compressed.huf. Then, run the decompression program to restore the original file as output.txt.
### Example:
**Compress the File:**
![Compression](https://github.com/DeepAryanSharma/FileZipper/blob/main/ImplementationScreenshots/compression.png)
![InputFileSIze](https://github.com/DeepAryanSharma/FileZipper/blob/main/ImplementationScreenshots/inputFileSize.png)
![CompressedFileSize](https://github.com/DeepAryanSharma/FileZipper/blob/main/ImplementationScreenshots/compressedFileSize.png)

**Decompress the File:**
![Decompression](https://github.com/DeepAryanSharma/FileZipper/blob/main/ImplementationScreenshots/decompression.png)
![OutputFileSize](https://github.com/DeepAryanSharma/FileZipper/blob/main/ImplementationScreenshots/outputFileSize.png)

## Contributing
Contributions are welcome! Please fork this repository and submit pull requests for any improvements or bug fixes.

## Contact
For any questions or feedback, please reach out to aryan153sharma@gmail.com .



   
