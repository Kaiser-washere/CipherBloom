<h1>CipherBloom - PurpleRose Decoder </h1>

<p>CipherBloom is a lightweight Python toolkit for decoding obfuscated data.  
It supports <b>Base64</b>, <b>zlib</b>, and <b>gzip</b>, automatically detecting the format and saving the decoded output as text or binary.</p>

<h2>Features</h2>
<p>
- Automatic format detection (Base64, zlib, gzip)<br>
- UTF‑8 text output when possible, binary fallback otherwise<br>
- Colorized CLI interface with a custom PurpleRose banner
</p>

<h2>Quick Start</h2>
<p>
<b>1.</b> Clone the repository:<br>
<pre><code>git clone https://github.com/yourusername/cipherbloom.git
cd cipherbloom
</code></pre>

<b>2.</b> Run the decoder:<br>
<pre><code>python core.py</code></pre>

<b>3.</b> Provide input:<br>
- Enter the path to your encoded file (e.g., <code>encoded.txt</code>)<br>
- Enter the desired output file name (e.g., <code>decoded.txt</code>)
</p>

<h2>📂 Project Structure</h2>
<pre>
cipherbloom/
│
├── core.py
├── base64_decoder.py
├── zlib_decoder.py
├── gzip_decoder.py
└── README.md
</pre>

<h2> License</h2>
<p>Released under the MIT License. Free to use, modify, and share.</p>
<h1>educational use only</h1>
