## **AI-Powered Web Scraper**

A very eazy webApp for extracting data from websites using AI.

### **How it Works:**

1. **Input URL:** Provide the target website's URL.
2. **Web Scraping:** The tool scrapes the website's content.
3. **AI Processing:** Natural Language Processing (NLP) is used to analyze the content.
4. **Data Extraction:** Based on your query, relevant information is extracted and presented.

### **Example: Extracting Product Information**

**Target Website:** [https://www.shopify.com/blog/best-ecommerce-sites](https://www.shopify.com/blog/best-ecommerce-sites)

**Prompt:** "Extract product names, prices, and ratings from the product listings."

**Output:**
| Product Name | Price | Rating |
|---|---|---|
| [Product 1] | [Price] | [Rating] |
| [Product 2] | [Price] | [Rating] |
| ... | ... | ... |

**Key Features:**

- **Flexibility:** Handles various website structures and content types.
- **Efficiency:** Uses AI for rapid data extraction.
- **Customizable:** Tailor prompts to extract specific information.
- **Scalable:** Can process large datasets.

**Get started:**

1. Clone the repository.
2. Install required libraries (requirements.txt).
3, download [Chrome Driver](https://developer.chrome.com/docs/chromedriver/downloads) for your OS and copy it to the root of the project directory. 
4. Run "streamlit run main.py" in your termenal   
5, The site will open in  google chrome.
 
inter the URL in the textbox 

press Scrape Website   button 

inter your  prompt.

**Note:** This website uses llama3 AI model to parce the data and required [Ollama](https://ollama.com/) on your system.
You can easily change it to use any other llm like Google Gemini or chat gpt, take a look to  parse.py file.  

## Contributing
Contributions to this project are welcome! If you find a bug, have an idea for an improvement, or want to contribute in any other way, please feel free to open an issue or submit a pull request.


## License

This project is licensed under the [GNU General Public License, version 2] - see the [LICENSE.md](LICENSE.md) file for details.