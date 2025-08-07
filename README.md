# Trendyol Scraper

A Python script to scrape seller information from Trendyol and export detailed results to a styled Excel file.

## Features

- Uses Selenium for browser automation
- Reads seller names from Excel
- Scrapes seller ratings, review counts, and more
- Exports results to Excel with colorful styles and filters

## Setup

1. **Install dependencies:**
   ```powershell
   pip install -r requirements.txt
   ```
2. **Download Edge WebDriver:**
   - [Microsoft Edge WebDriver](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/)
   - Place the executable in your PATH or specify its location in the script.
3. **Prepare your Excel file:**
   - Create an Excel file with a column named `Mağaza Adı` in `Sheet1`.
   - Update the script to use your file path.

## Usage

1. Edit `SellerDataScraper.py` and set your Excel file path:
   ```python
   data = pd.read_excel(r"YOUR_EXCEL_FILE_PATH.xlsx", sheet_name="Sheet1")
   ```
2. Run the script:
   ```powershell
   python deneme.py
   ```

## Output

- The script creates `Trendyol Satıcı Bilgileri (Detaylı).xlsx` with:
  - **Colorful header** (blue background, white bold text)
  - **Styled cells** (Calibri font, centered)
  - **Number formatting** for review and comment counts
  - **Auto-sized columns**
  - **Excel table with filters**

## Example Screenshot

![Excel Styles Example](https://user-images.githubusercontent.com/123456789/your-example-image.png)

## License

MIT
