# Azure Search OpenAI Demo

This application demonstrates the integration of Azure Search with OpenAI. It provides a backend service that allows users to search and retrieve information using natural language queries.

## Features

- **Natural Language Search**: Use OpenAI's language model to perform searches using natural language.
- **Azure Search Integration**: Leverage the power of Azure Search to index and retrieve documents.
- **RESTful API**: A simple RESTful API to interact with the search service.

## Prerequisites

- Azure Subscription
- OpenAI API Key
- Azure Search Service

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/azure-search-openai-demo.git
    ```
2. Navigate to the backend directory:
    ```bash
    cd azure-search-openai-demo/app/backend
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Configuration

1. Create a `.env` file in the backend directory with the following content:
    ```env
    AZURE_SEARCH_SERVICE_NAME=your_search_service_name
    AZURE_SEARCH_API_KEY=your_search_api_key
    OPENAI_API_KEY=your_openai_api_key
    ```

## Usage

1. Start the backend service:
    ```bash
    python app.py
    ```
2. The service will be available at `http://localhost:5000`.

## API Endpoints

- `GET /search`: Perform a search query.
    - **Parameters**: `query` (string) - The search query.
    - **Response**: JSON object containing search results.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Azure Search](https://azure.microsoft.com/en-us/services/search/)
- [OpenAI](https://www.openai.com/)
