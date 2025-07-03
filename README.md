# CompactCrypt

A web application for secure file compression and encryption.

## Features
- Compress and decompress files (Huffman coding and gzip)
- Encrypt and decrypt files using AES encryption
- User-friendly web interface (Flask)

## How to Run

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

2. Start the server:
   ```
   python app.py
   ```

3. Open your browser and go to `http://127.0.0.1:5000/`

## File Structure

- `app.py` - Flask backend
- `haffman.cc` - Huffman coding (C++)
- `encrypted_decrypted.py` - AES encryption/decryption
- `templates/` - HTML templates
- `static/` - CSS, JS, images

## License
MIT
