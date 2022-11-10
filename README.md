# File-Compressor-Decompressor

This project is based on Huffman Coding, a lossless, bottom-up compression algorithm. It can compress and decompress any text files.

To learn more about Huffman Coding and its applications in Information Theory read this article.

# Implementation in Project
This project supports two functions:
1) Encode: Compresses input file passed.
2) Decode: Decompresses Huffman coded file passed back to its original file.

# To RUN THIS : 
1. Open cmd in the same folder where your files are stored.
2. Now type  "g++ encode.cpp -o main"  , press enter.
3. Now type "main input.txt Compress.huf" , press enter.
4. A compressed file with Compress.huf is now creted.
5. For decoding replace encode.cpp with decode.cpp in step 2 , and intput.txt with Compress.huf.

# Result: 
This project is just an implementation of Huffman coding, it is not as efficient as the compression algorithm used currently to compress files.

# Example: 
inputFile.txt (2.2MB) is compressed to compressedFile.huf (1.1MB) file and decompressed back to ouputFile.txt (2.2MB).
