

A conversational data analysis dashboard that converts natural language questions into real Pandas and Matplotlib code.

---

## Overview

A conversational data analysis dashboard allows users to upload a dataset and explore it by asking questions like:

"Show me a bar chart of profit by region"

The system generates real Python code, executes it, and displays charts, tables, or statistics.

---

## Features

- Upload CSV, Excel, or TSV files
- Ask natural-language questions
- Get real charts and tables (not text)
- See the generated Python code
- No automatic recommendations — request-driven only

---

## How It Works

1. User uploads a file  
2. User asks a question  
3. LLM converts the question into Pandas + Matplotlib code  
4. The code is validated and executed  
5. Output is displayed in the app  

Schema checks prevent invalid plots or crashes.

---

## Tech Stack

- Streamlit
- Pandas
- Matplotlib
- LLM API (NL → Python)

---

## Constraints

- One dataset at a time
- Limited by Streamlit compute and LLM rate limits
- Assumes reasonably clean tabular data

---

## Goal

To demonstrate how conversational interfaces can drive real executable analytics.

