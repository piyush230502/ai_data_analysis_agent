# 📊 AI Data Analysis Agent

An AI data analysis Agent built using the Agno Agent framework and OpenAI's GPT-4o model. This agent helps users analyze their data (CSV, Excel files) through natural language queries, powered by OpenAI's language models and DuckDB for efficient data processing - making data analysis accessible to users regardless of their SQL expertise.

## ✨ Features

- 📤 **File Upload Support**: 
  - Upload CSV and Excel files
  - Automatic data type detection and schema inference
  - Support for multiple file formats

- 💬 **Natural Language Queries**: 
  - Convert natural language questions into SQL queries
  - Get instant answers about your data
  - No SQL knowledge required

- 🔍 **Advanced Analysis**:
  - Perform complex data aggregations
  - Filter and sort data
  - Generate statistical summaries
  - Create data visualizations

- 🎯 **Interactive UI**:
  - User-friendly Streamlit interface
  - Real-time query processing
  - Clear result presentation

## 🚀 How to Run

1. **Setup Environment**
   ```bash
   # Clone the repository
   git clone https://github.com/Shubhamsaboo/awesome-llm-apps.git
   cd ai_agent_tutorials/ai_data_analysis_agent

   # Install dependencies
   pip install -r requirements.txt
   ```

2. **Configure API Keys**
   - Get OpenAI API key from [OpenAI Platform](https://platform.openai.com)
   - Add the key to your environment variables or directly in the app

3. **Run the Application**
   ```bash
   streamlit run ai_data_analyst.py
   ```

## 📋 Usage

1. Launch the application using the command above
2. Provide your OpenAI API key in the sidebar of Streamlit
3. Upload your CSV or Excel file through the Streamlit interface
4. Ask questions about your data in natural language
5. View the results and generated visualizations

## 📊 Example Queries

- "What is the average sales by region?"
- "Show me the top 10 customers by revenue"
- "Create a bar chart of monthly sales for 2023"
- "What's the correlation between customer age and purchase amount?"
- "Find outliers in the transaction data"

## 🛠️ Technology Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **LLM**: OpenAI GPT-4o
- **Data Processing**: DuckDB, Pandas
- **Visualization**: Matplotlib, Plotly
- **Framework**: Agno Agent

## 📝 Requirements

- Python 3.9+
- OpenAI API key
- Internet connection for API calls

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 🙏 Acknowledgements

- [OpenAI](https://openai.com/) for providing the GPT-4o model
- [Streamlit](https://streamlit.io/) for the interactive UI framework
- [DuckDB](https://duckdb.org/) for efficient data processing
- [Agno](https://github.com/Shubhamsaboo/agno) for the agent framework
