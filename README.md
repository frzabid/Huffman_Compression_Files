
# Huffman Text Compression  

This Python project uses Huffman Encoding for compressing and decompressing text files. It supports `.txt`, `.docx`, and `.pdf` formats and provides efficient storage with metadata for decoding.

## Features  
- Compress text files using Huffman Encoding.  
- Decompress files back to their original text.  
- Supports `.txt`, `.docx`, and `.pdf` file formats.  
- Automatic handling of file names for compressed and decompressed files.  
- Saves metadata in `compressed_files.json` for easy decoding.  

## Requirements  
- Python 3.6+  
- Libraries:  
  - `PyPDF2`  
  - `python-docx`  

Install dependencies with:  
```bash
pip install -r requirements.txt
```  

## Usage  

1. Clone the repository:  
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Run the script:  
   ```bash
   python huffman_compression.py
   ```

3. Choose an operation:  
   - **1**: Compress a file.  
   - **2**: Decompress a file.

4. Provide the file path when prompted.  

## Outputs  
- Compressed binary file: `*_compressed.bin`.  
- Metadata stored in `compressed_files.json`.  
- Decompressed file: `*_decompressed.txt`.

## Notes  
- Ensure file paths are correct and accessible by the script.  
- The `compressed_files.json` file must remain in the same directory for proper decompression.  

## License  
This project is licensed under the MIT License.
