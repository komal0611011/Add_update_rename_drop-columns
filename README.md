# Add_update_rename_drop-columns

## 📄 Student DataFrame Processing

This Python script uses **Pandas** to perform various data cleaning and transformation operations on a student dataset.

### ✅ Key Operations:

- Created a DataFrame with student info (Name, Age, Location, Marks, etc.)
- Renamed `Location` column to `City`
- Added columns:
  - `Performance` → "Excellent" if Marks ≥ 90, else "Good"
  - `Passed` → True if Marks ≥ 70
  - `Remark` → "Topper", "Average", or "Needs Improvement" based on Marks
- Dropped the `Status` column
- Added a new student record (Nisha from Kolkata)
- Filtered out rows where Marks < 70
- Updated "Ayesha"'s age to 23
- Dropped the row for "Simran"
- Reset DataFrame index

### 📌 Libraries Used:
- `pandas`
