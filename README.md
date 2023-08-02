# Advanced Natural Language to SQL with LLMs

This repository demonstrates the cutting-edge capabilities of generative AI in the realm of database querying. The Jupyter notebook within showcases the application of OpenAI's `gpt-3.5-turbo-16k-0613` model in transforming complex natural language queries into SQL queries, which are then executed on a SQLite database.

## Project Overview

The project employs the LangChain SQLAgent, an advanced tool that leverages the power of Large Language Models (LLMs) to convert natural language queries into SQL queries. The SQLAgent's distinguishing feature is its ability to make informed decisions based on user input, utilizing a suite of tools until it achieves a satisfactory answer. This includes the ability to recover from errors in executing the generated SQL, interpreting the error in a subsequent LLM call, and rectifying the issue.

The notebook demonstrates this capability by connecting to a SQLite database and executing a series of complex SQL queries generated from natural language inputs. The SQL queries are generated using a prompt template that provides instructions to the AI model on how to understand the input question, generate a SQL query, and analyze the results.

## Key Features

- **Complex SQL Query Generation**: The notebook demonstrates the ability to generate complex SQL queries from natural language inputs. This includes queries involving multiple joins, aggregations, and conditional statements.

- **Error Recovery**: The SQLAgent is capable of recovering from errors in executing the generated SQL. It interprets the error in a subsequent LLM call and rectifies the issue, ensuring a high success rate in query execution.

- **Prompt Engineering**: The notebook showcases advanced prompt engineering techniques to guide the AI model in generating the correct SQL queries. It uses a default template that instructs the AI model on how to understand the input question, generate a SQL query, and analyze the results.

- **SQLite Database Interaction**: The notebook demonstrates how to interact with a SQLite database using Python's sqlite3 module. It shows how to connect to an existing database, execute SQL queries, fetch query results, and close the database connection.

- **LangChain Library Usage**: The notebook shows how to use various components of the LangChain library, including SQLDatabase, ChatOpenAI, SQLDatabaseChain, SQLDatabaseSequentialChain, and ConversationBufferMemory.

## Getting Started

To run the notebook, you will need to install the `langchain` and `openai` Python libraries. You will also need to provide your OpenAI API key.

```bash
pip install langchain openai
```

## Usage

The notebook provides a step-by-step guide on how to use the LangChain SQLAgent to generate and execute SQL queries from natural language inputs. It includes examples of complex SQL queries and demonstrates how to handle errors and recover from them.

## Conclusion

This project showcases the potential of generative AI in making databases more accessible and easier to use. By converting natural language queries into SQL queries, we can bridge the gap between non-technical users and databases, opening up new possibilities in data analysis and business intelligence.
