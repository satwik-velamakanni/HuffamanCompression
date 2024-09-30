# Huffman Compression Tool in C++

This project implements a file compression utility using the **Huffman Coding Algorithm** in C++. Huffman coding is a powerful **lossless data compression technique** that assigns variable-length binary codes to characters based on their frequency in the input file. The tool is designed to compress and decompress files efficiently by constructing an optimal binary tree for encoding and decoding data.

## Key Features

- **Lossless Compression:** Utilizes the Huffman algorithm to compress data without any loss of information.
- **File Handling:** Supports reading files from the system for compression and writing the compressed data to the file system.
- **Huffman Tree Construction:** Dynamically builds a custom binary tree based on character frequencies from the input data.
- **Binary File Compatibility:** Capable of compressing both text and binary files.
- **Full Decompression Support:** Restores compressed files to their original form using the Huffman tree.

## Compression Workflow

1. **Character Frequency Analysis:** Reads the file and counts how often each character occurs.
2. **Building the Huffman Tree:** Constructs a binary tree where frequently occurring characters get shorter binary codes.
3. **Compression Process:** Replaces each character in the file with its unique binary code, reducing the overall file size.
4. **Decompression Process:** Decodes the compressed file back to its original state by traversing the Huffman tree.
