# GenAI Financial Bot
 
# Financial Chatbot

A Python-based financial chatbot application that answers queries related to the financial data of major companies like **Apple**, **Microsoft**, and **Tesla**. The chatbot uses a dataset containing financial metrics, including revenue, net income, assets, and liabilities for the years 2022, 2023, and 2024. 

This project is built with Flask for the backend, utilizing Python libraries like Pandas for data manipulation. The frontend is powered by HTML, CSS, and JavaScript for a seamless user interface.

## Features

- **Query Financial Data**: Users can ask questions about specific financial metrics (e.g., total revenue, net income, assets, liabilities, etc.) for the given companies and years.
- **Dynamic Responses**: The chatbot provides answers based on the dataset, offering real-time data for the requested company and year.
- **User-Friendly Interface**: The application features a clean and responsive web interface to interact with the chatbot.
- **Multiple Companies Supported**: The chatbot can handle queries for companies like Apple, Microsoft, and Tesla.
- **Flexible Data Format**: The data is dynamically loaded from a CSV file, allowing for easy updates and extensions.

## Screenshots

![Screenshot 2025-01-05 210153](https://github.com/user-attachments/assets/87c7f628-25b3-4b17-a40a-2f413a36357e)


![Screenshot](screenshot1.png)

## Project Structure

The project structure is as follows:

GEN AI/ ├── static/ │ ├── script.js # JavaScript file for frontend interaction │ └── style.css # CSS file for styling the web page ├── templates/ │ └── index.html # HTML template for the chatbot UI ├── Data Extraction and Initial Analysis.csv # Dataset file containing financial data ├── Financial_chatbot.py # Python script to run the Flask web server and handle logic ├── requirements.txt # Python dependencies for the project └── README.md # Project documentation


- **static/**: Contains static files like JavaScript and CSS.
- **templates/**: Contains HTML files to render the web pages.
- **Data Extraction and Initial Analysis.csv**: The CSV file that contains financial data for Apple, Microsoft, and Tesla.
- **Financial_chatbot.py**: The main Python file that starts the Flask web server and manages the chatbot logic.
- **requirements.txt**: Lists all Python dependencies that need to be installed to run the application.
- **README.md**: Documentation for the project.

## Installation

To get started with the Financial Chatbot project, follow the instructions below:

### Prerequisites

- Python 3.x
- pip (Python package manager)

### Steps to Install

1. **Clone the repository** to your local machine:

    ```bash
    git clone https://github.com/your-username/financial-chatbot.git
    cd financial-chatbot
    ```

2. **Install the required Python dependencies**:

    You can install the dependencies listed in the `requirements.txt` file using pip:

    ```bash
    pip install -r requirements.txt
    ```

    This will install all the necessary libraries like Flask and Pandas to run the application.

3. **Place the dataset file**: Ensure that the `Data Extraction and Initial Analysis.csv` file is present in the project directory. This file contains the financial data that the chatbot will use to answer queries.

## Running the Application

To run the financial chatbot locally, follow these steps:

1. **Navigate to the project directory** and run the Flask application:

    ```bash
    python Financial_chatbot.py
    ```

2. **Access the chatbot**: Open your web browser and navigate to `http://127.0.0.1:5000` to interact with the chatbot.

    The interface will prompt you to enter queries related to financial data for Apple, Microsoft, or Tesla, for the years 2022, 2023, or 2024.

## Usage

Once the application is running, open the browser and interact with the chatbot:

1. **Ask a question**: Type in questions like:
   - "What was Apple's revenue in 2023?"
   - "Tell me about Tesla's net income in 2024."
   - "What is Microsoft's total assets for 2022?"

2. The chatbot will respond with the relevant financial data from the CSV file.

### Example Interaction:

**User**: What was Apple's revenue in 2023?

**Chatbot**: Apple's revenue for 2023 was $390 billion.

## Technologies Used

- **Python**: The main programming language for the backend logic.
- **Flask**: A micro web framework for Python that serves the backend API.
- **Pandas**: Python library for data manipulation and analysis. It is used to load and query the financial dataset.
- **HTML/CSS**: For building the frontend interface.
- **JavaScript**: For frontend interactivity.

## Contributing

Contributions to the Financial Chatbot project are welcome! You can contribute by:

- Reporting bugs or issues
- Suggesting new features or improvements
- Forking the repository and submitting pull requests

### How to Contribute

1. **Fork** the repository to your own GitHub account.
2. **Clone** the forked repository to your local machine.
3. Create a new branch for your feature or bug fix.
4. **Commit** your changes and push them to your forked repository.
5. **Create a Pull Request** to merge your changes into the main repository.

Please ensure that your code follows the project’s style guidelines and passes all tests before submitting a pull request.


## Acknowledgments

- **Flask** for providing a simple and powerful web framework.
- **Pandas** for making data manipulation easy.
- **OpenAI** for providing inspiration for the chatbot logic and interaction.

## Contact

For any questions, suggestions, or collaboration ideas, feel free to contact:

- Email: surjanmukherjeeimp@gmail.com
- LinkedIn: [Surjan Mukherjee](https://www.linkedin.com/in/surjan-mukherjee-90aa721bb/)

---

This detailed `README.md` should give a clear understanding of the project, installation steps, usage, and how others can contribute. Let me know if you need any adjustments or further elaboration!
