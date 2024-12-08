# AI News Summarization and WhatsApp Automation

This project leverages AI to scrape, summarize, and send news articles directly to WhatsApp, solving the challenge of sharing lengthy news articles quickly with colleagues or contacts. The AI summarizes the content, making it easier to stay updated without needing to read the entire article.

## Features
- **Article Scraping**: Scrapes articles from provided URLs.
- **AI Summarization**: Uses OpenAI and Gemini to generate concise summaries of articles.
- **WhatsApp Automation**: Sends summarized articles to WhatsApp contacts automatically.
- **Customizable**: You can select up to 5 news articles to send summaries of, along with the WhatsApp numbers to send them to.

## Workflow Overview

1. **Process URLs**: Input the URLs of the news articles you want to share.
2. **Scrape Articles**: The system scrapes the articles to extract relevant information.
3. **Summarize Content**: The content is summarized using OpenAI and Gemini models to create concise summaries.
4. **Generate WhatsApp Message**: The summarized content is formatted into a WhatsApp message, with a link to the full article.
5. **Send WhatsApp Message**: The message is scheduled and sent to the designated WhatsApp numbers.
6. **Final Check**: Ensures that the message was successfully sent or logs any errors.

## Libraries Used
- **pywhatkit**: For WhatsApp automation.
- **tiktoken**: For efficient tokenization with GPT models.
- **BeautifulSoup**: For web scraping and extracting article content.
- **OpenAI API**: Used for article summarization.
- **Gemini AI**: Alternative AI model used for summarization.

## Future Improvements
- **UI for Selecting News**: A user interface where you can select specific topics (e.g., "AI Tools"), and the UI will show the latest 10 news headlines. You can then select up to 5 articles to summarize.
- **Customizable WhatsApp Numbers**: Let users input the WhatsApp numbers where summaries should be sent.
- **Advanced Automation**: Improve the automation to send news at specified times or intervals.

## How to Use
1. Clone this repository.
    ```bash
    git clone https://github.com/rohitmane2001/weekend_project_8dec2024.git
    ```
2. Install the required dependencies.
    ```bash
    pip install -r requirements.txt
    ```
3. Set up the configuration (WhatsApp API credentials, OpenAI API keys, etc.).
4. Run the script to start the automation.
    ```bash
    python main.py
    ```

## Contributing
Feel free to open issues or submit pull requests for improvements. Contributions are welcome!

## License
This project is licensed under the MIT License.

---

Feel free to modify and expand upon this as needed based on your project's specific needs and details!
