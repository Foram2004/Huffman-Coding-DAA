🔤 Huffman Compression Algorithm <br>
A Python implementation of the Huffman coding algorithm for lossless data compression. This program compresses text by assigning variable-length binary codes to characters based on their frequency, with more common characters getting shorter codes.<br>

🎯 Overview <br>
Huffman coding is a classic compression algorithm that reduces the size of data by encoding frequent characters with shorter bit sequences and less frequent characters with longer ones. This implementation demonstrates the complete process from character frequency analysis to binary encoding. <br>

🧠 How It Works <br>
The algorithm follows these key principles: <br> 
Frequency Analysis: Count occurrences of each character <br>
Binary Tree Construction: Build a Huffman tree where frequent characters are closer to the root <br>
Prefix Codes: Generate codes where no code is a prefix of another <br>
Variable-Length Encoding: Replace characters with their binary codes <br>
 
✨ Features <br>
✅ Automatic Frequency Analysis: Calculates character frequencies from input text <br>
✅ Huffman Tree Generation: Builds optimal prefix code tree <br>
✅ Binary Code Assignment: Generates efficient variable-length codes <br>
✅ Compression Metrics: Shows before/after size comparison <br>
✅ Visual Tree Display: Shows each level of the Huffman tree construction <br>
✅ Binary Output: Displays compressed binary representation <br>
