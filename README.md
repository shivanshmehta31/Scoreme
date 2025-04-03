

# PDF Extracter  

```markdown
# Table Extraction from PDFs to Excel

## Overview
This project extracts tables from system-generated PDFs and stores them in an Excel sheet. Unlike traditional methods, this tool does **not** rely on **Tabula, Camelot, or image conversion**.

## Features
- **Accurate table extraction** from PDFs
- **No dependency on Tabula, Camelot, or OCR-based approaches**
- **Exports extracted tables** directly to an Excel sheet
- **Handles multiple PDFs efficiently**

## Installation
Clone the repository:
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage
1. Place the PDFs in the `input_pdfs` directory.
2. Run the extraction script:
   ```bash
   python extract_tables.py --input input_pdfs --output output.xlsx
   ```
3. The extracted tables will be saved in `output.xlsx`.

## Files in This Repository
- `source_code.ipynb` – Jupyter Notebook for extracting tables from PDFs
- `test3 (1).pdf` – Sample input PDF for testing
- `test3_output.xlsx` – Extracted tables from the sample PDF

## Future Improvements
- Enhance table structure detection for complex layouts
- Support for scanned PDFs using OCR (optional)
- Web-based interface for easy uploads and downloads

## Contributing
Feel free to fork this repository and submit pull requests. Contributions are welcome!

## License
This project is licensed under the MIT License.

---

Let me know if you want to tweak anything! 🚀
