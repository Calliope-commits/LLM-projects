# MySQL Query Generator using LangChain

## Overview
This project demonstrates how to create an intelligent MySQL query generator using LangChain. It leverages large language models (LLMs) to dynamically generate SQL queries based on natural language inputs. The system is designed to understand the user's question, identify relevant database tables, and generate the appropriate SQL query for execution.

The notebook includes functionality to:
- Parse the user's question and generate a relevant SQL query.
- Identify which tables in the database are relevant to the user's query.
- Answer follow-up questions using context memory.
- Provide rephrased or optimized answers.

## Key Features
- **Dynamic Table Selection**: Identifies relevant database tables for each user query.
- **SQL Query Generation**: Generates syntactically correct SQL queries based on user input.
- **Memory**: Stores chat history for follow-up questions, allowing the model to reference past interactions.
- **Rephrasing**: Outputs optimized answers or alternative SQL query formats.

## Requirements
- LangChain
- OpenAI
- Pandas
- Jupyter Notebook environment
