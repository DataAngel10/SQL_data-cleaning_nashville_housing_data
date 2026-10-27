# 🧹 SQL Data Cleaning - Nashville Housing

In this project, I worked to clean, structure, and optimize a raw real estate dataset using SQL, transforming messy records into analysis ready data.

## 📊 Dataset Info
* **Source:** Nashville Housing Data (`nashville housing data.csv`)
* **Rows:** 31,171 (reduced to 31,121 after deduplication)

## 🛠️ Key SQL Tools & Techniques
* **NULL Handling:** `SELF JOIN`, `COALESCE()`
* **String Manipulation:** `SUBSTRING()`, `LOCATE()`, `SUBSTRING_INDEX()`
* **Conditional Logic:** `CASE WHEN`
* **Advanced Queries:** CTEs (`WITH`), Window Functions (`ROW_NUMBER()`)
* **Schema Updates:** `ALTER TABLE` (`ADD`/`DROP COLUMN`), `UPDATE`, `DELETE`

## 📂 Project Structure
```text
├── Data cleaning_Nashville housing data.sql    # Main SQL script
├── nashville housing data.csv                  # Raw dataset file
├── Nashville Housing Data without null.csv.    # Without null dataset file
└── assets/                                     # Folder containing result screenshots
    ├── SQL_nashville_image_1.png
    ├── SQL_nashville_image_2.png
    ├── SQL_nashville_image_3.png
    ├── SQL_nashville_image_4.png
    ├── SQL_nashville_image_5.png
    ├── SQL_nashville_image_6.png
    ├── SQL_nashville_image_7.png
    ├── SQL_nashville_image_8.png
    ├── SQL_nashville_image_9.png
    ├── SQL_nashville_image_10.png
    ├── SQL_nashville_image_11.png
    └── SQL_nashville_image_12.png
