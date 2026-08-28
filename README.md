Storage Test File Generator
A simple client-side web tool to generate dummy files from 10 KB to 100 GB for testing storage devices, upload limits, download speeds, and bandwidth.
Everything runs in your browser — no server, no uploads, no tracking.
Features
Generate files from 10 KB up to 100 GB
Quick presets (10 KB → 100 GB)
Content options:
Zeros — fast generation, highly compressible
Random bytes — better for realistic write-speed tests
Streams large files directly to disk (File System Access API)
Progress bar + cancel support
Single HTML file, no dependencies
How to use
Open `file-generator.html` in a modern browser
Set the desired size and filename
Choose content type
Click Generate & Save File
> **Tip:** For files larger than a few hundred MB, use Chrome, Edge, or Opera for the best experience.
Browser support
Feature	Chrome / Edge / Opera	Firefox	Safari
Small–medium files (Blob)	✅	✅	✅
Large files (streaming)	✅	❌	❌
License
MIT
