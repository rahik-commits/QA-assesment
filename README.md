# Google Search Suggestions Extractor

This project is a Python automation script that **extracts Google search suggestions** for a list of keywords stored in an Excel file. The script uses **Selenium WebDriver** to search Google and retrieves the longest and shortest suggestions for each keyword. The results are then saved back into the Excel file.

## 🚀 Features
- Reads keywords from **Excel.xlsx** .
- Uses **Selenium WebDriver** to fetch Google search suggestions.
- Extracts the **longest and shortest search suggestions**.
- Saves results in **(Longest)** and **(Shortest)**.
- Automatically detects the correct sheet based on the **current day**.

---

## 📂 File Structure
   QA_ASSESMENT/
├── 📄 test.py # Main script
├── 📄 Excel.xlsx # Input Excel file (contains keywords)
├── 📄 README.md # Project documentation


## ▶️ How to Run
# Step 1: Ensure 'Excel.xlsx' is closed before running the script.

# Step 2: Open a terminal or command prompt and navigate to the project folder
cd path/to/QA_ASSESMENT

# Step 3: Run the Python script
python test.py

# The script will:
 - Open Google
 - Search each keyword from 'Excel.xlsx'
 - Retrieve search suggestions
 - Save results in the same Excel file

# Step 4: Once completed, check 'Excel.xlsx' for updated results in:
 - Column D (Longest Suggestion)
 - Column E (Shortest Suggestion)
