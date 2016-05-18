Magic Number
===============

Ruby gem that allows to verify if file content is in accordance with it's extension and prevent fake uploads to your site.

Installation
------------

Add this into your Gemfile and then run bundle install

    gem 'MagicNumber', '~> 0.0.1'

### What is a magic number?
Magic number is a digital signature that each filetype contains. It could be use to verify the format of a file, so this gem uses it to check whether a file is truly as its extension says

### Supported file types

- PDF
- DOCX
- XLSX
- PPTX
- VSDX
- DOC
- XLS
- PPT
- JPG
- PNG
- JPEG
- GIF
- TIF
- TIFF
- PIC
- ICO
- BMP
- AVI
- PSD
- WAV
- MP3
- ISO
- FLAC
- MID
- MIDI
- ASF
- OGG
- OGA
- OGV
- MKV
- MKA
- MKS
- MK3D
- WEBM
- Z
- BZ2
- CR2
- ZIP
- RAR
- TAR
- DMG
- VMDK
- EXE
- JAR
- CLASS
- SEA
- YTR
- DBA
- MSG
- CRX
- FH8

Usage
-----
This gem provides is_real? method to check file authenticity

### Example of usage
```erb
  file_real = MagicNumber.is_real?("/tmp/document.pdf")
```

TODO
-----
 · Add function to get real file type.

Author
-----
Adrián Fernández <adrian@adrian-fernandez.net>

[http://www.adrian-fernandez.net](http://www.adrian-fernandez.net)

[@adrian-fernandez](https://twitter.com/adrianfdez14)

