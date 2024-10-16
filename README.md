
# Financial Analyst System using LangChain and Ollama

This project implements a financial analyst system using LangChain and Ollama. The system allows users to input queries related to finance, such as stock analysis, market trends, and company reports, and returns insightful and organized responses.

## Features

- **Interactive Financial Queries**: Users can input finance-related questions, and the system responds with structured, useful answers.
- **LangChain Integration**: Utilizes LangChain's `PromptTemplate` to format queries before sending them to the model for accurate results.
- **Ollama Model**: Uses Ollama for AI-driven query handling, delivering concise and relevant financial insights.
- **Continuous Interaction**: The system stays active and continuously processes user inputs until explicitly stopped.
- **Error Handling**: Robust error handling ensures smooth operations and prevents system crashes.

## Requirements

To run this system, ensure you have the following libraries installed:

```bash
pip install ollama langchain
```

## Usage

1. **Clone the repository**:
   
   ```bash
   git clone https://github.com/TamerOnLine/financial-analyst-system.git
   cd financial-analyst-system
   ```

2. **Run the system**:

   Run the following command to start interacting with the financial analyst system:

   ```bash
   python financial_analyst_system.py
   ```

3. **Input Queries**: 

   Once the system is running, you can input any finance-related query. For example:

   ```bash
   What are the current trends in the stock market?
   ```

   The system will respond with detailed, organized insights.

## Code Structure

- `financial_analyst_system.py`: The main script that initializes the LangChain and Ollama integration, processes user queries, and returns formatted answers.
- `templates/`: Contains the prompt templates used to structure user questions before sending them to the model.

## Example

```bash
Input: What are the most profitable tech stocks in 2024?

Response:
- Stock A: Detailed performance metrics
- Stock B: Insights on market position
...
```

## Future Improvements

- **Data Integration**: Add real-time financial data integration from APIs to enhance response accuracy.
- **Advanced Analysis**: Implement deeper financial analysis and machine learning-based predictions.

## Contributing

We welcome contributions! Please follow the steps below to contribute:

1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

**Developed by [Tamer](https://www.linkedin.com/in/tameronline)**.
