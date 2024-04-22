# Hacker News Login Script

This repository contains a Python script for logging into Hacker News using the requests and BeautifulSoup libraries. The script allows users to provide their username and password for authentication and checks if the login was successful.

## How It Works

The `login.py` script performs the following steps:

1. It imports the necessary libraries: `requests` for making HTTP requests and `BeautifulSoup` for parsing HTML.
2. The script prompts the user to enter their Hacker News username and password.
3. It creates a session using the `requests.Session()` object to maintain the login state.
4. The script sends a POST request to the Hacker News login page (`https://news.ycombinator.com/login`) with the provided username and password.
5. It parses the response HTML using BeautifulSoup to check if the login was successful.
6. If the login is successful, it prints "Successfully logged in"; otherwise, it prints "Authentication Error".

## Usage

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/hacker-news-login-script.git
    ```

2. Navigate to the repository directory:

    ```bash
    cd hacker-news-login-script
    ```

3. Open the `hacker_news_login.py` file and replace the `USERNAME` and `PASSWORD` variables with your Hacker News credentials.

4. Run the script using Python:

    ```bash
    python login.py
    ```

5. If the login is successful, you will see the message "Successfully logged in." Otherwise, you will see "Authentication Error."

## Dependencies

- Python 3.x
- requests library
- BeautifulSoup library

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
