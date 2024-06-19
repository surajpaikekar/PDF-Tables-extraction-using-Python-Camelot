## Steps:

1. **Install the camelot-py library**
2. **Install the pydf2==1.26.0**
3. **Install the Ghostscript**

**Note:** 
- *Camelot* uses `PdfReader` from the `pypdf2` library. Therefore, `read_pdf` is not supported in `pypdf2` versions 3.0.2 or above.
- *You need to install a compatible `pypdf2` version*, i.e., 1.26.0.
- The *Camelot library requires Ghostscript* to be installed and available on the system PATH. You can download and install Ghostscript from the official website: [Ghostscript](https://www.ghostscript.com/download.html)

- **After installing Ghostscript**, make sure to add the Ghostscript bin and lib directories to your system's PATH environment variable. The typical paths are:
  - **Windows:** `C:\Program Files\gs\gs9.55.0\bin` and `C:\Program Files\gs\gs9.55.0\lib`

### Verify Ghostscript Installation

#### Windows:
- Open a new command prompt or PowerShell window.
- Type `gswin64c.exe -version` (or `gswin32c.exe` for 32-bit systems) and press Enter.
- Verify that Ghostscript is installed and available.


#### Documentation Links: 
- [Camelot](https://camelot-py.readthedocs.io/en/master/user/quickstart.html#read-the-pdf)
- [pypdf2](https://pypdf2.readthedocs.io/en/3.0.0/user/extract-text.html#using-a-visitor)
- [Ghostscript](https://ghostscript.com/releases/)
