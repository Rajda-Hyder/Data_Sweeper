# Data Sweeper

## 💿 Overview

Data Sweeper is a Streamlit-based web application that allows users to upload, clean, convert, and visualize CSV and Excel files seamlessly. With built-in data transformation options, users can efficiently manage datasets for further analysis.

## ✨ Features

- 📂 **Upload multiple files** (CSV or Excel)
- 🔎 **Preview the dataset** (first five rows)
- 🧹 **Data cleaning options**
  - Remove duplicates
  - Fill missing numeric values with the column mean
- 📌 **Select specific columns** for conversion
- 📊 **Basic data visualization** (bar chart of numerical data)
- ♋ **File conversion options**
  - Convert CSV to Excel and vice versa
  - Download the processed file

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- Streamlit
- Pandas

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/Data_Sweeper.git
   cd Data_Sweeper
   ```
2. Install the required dependencies:
   ```sh
   pip install streamlit pandas openpyxl
   ```

### Running the Application

Start the Streamlit application by running:

```sh
streamlit run app.py
```

## 📌 Usage

1. Upload one or more CSV or Excel files.
2. View the dataset preview.
3. Choose cleaning options (remove duplicates, fill missing values).
4. Select specific columns to keep.
5. Enable visualization (bar chart for numerical data).
6. Choose conversion type (CSV or Excel) and download the transformed file.

## 🛠 Technologies Used

- **Streamlit** - For building the web app
- **Pandas** - For data manipulation
- **Python** - Backend processing

## 📝 License

This project is open-source and available under the MIT License.

## 💡 Contributing

Feel free to fork the repository and submit pull requests. Suggestions and feature improvements are always welcome!

## 📬 Contact

For any questions or issues, reach out via GitHub Issues.

