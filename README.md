📊 Consoleflare Analytics Portal

An interactive Data Analytics Portal built with Streamlit, Pandas, and Plotly Express.
This app allows you to upload CSV or Excel files, explore datasets, view summaries, perform groupby operations, and generate interactive visualizations.

🚀 Features

📂 Upload CSV or Excel files.

📊 View dataset preview, top & bottom rows, data types, and column names.

📈 Statistical summary of the dataset.

🔢 Value count analysis with bar, line, and pie charts.

🧩 Groupby operations with aggregation functions (sum, mean, max, min, median, count).

🎨 Interactive visualizations: line, bar, scatter, pie, sunburst.

✅ Simple and user-friendly interface.

🛠️ Installation

Clone this repository (or copy the code into a file named app.py):

git clone https://github.com/yourusername/consoleflare-analytics-portal.git
cd consoleflare-analytics-portal


Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows


Install dependencies:

pip install -r requirements.txt


If you don’t have a requirements.txt, create one with:

streamlit
pandas
plotly
openpyxl   # For Excel file support

▶️ Usage

Run the app locally with:

streamlit run app.py


Then open your browser at:
👉 http://localhost:8501

📂 How to Use

Upload a .csv or .xlsx file using the uploader.

Explore dataset details in different tabs:

Summary → Rows, columns, and statistical summary.

Top & Bottom Rows → Preview dataset head & tail.

Data Types → Column data types.

Columns → List of all column names.

Perform Value Count analysis on categorical columns with charts.

Use Groupby Section to aggregate data and generate visualizations.

🖼️ Screenshots (Optional)

(Add screenshots of your app here for better presentation)

📌 Requirements

Python 3.8+

Streamlit

Pandas

Plotly Express

Openpyxl

🤝 Contribution

Feel free to fork this project and submit pull requests.
If you find bugs or have suggestions, open an issue!

📜 License

This project is licensed under the MIT License.
