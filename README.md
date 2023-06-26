# ChatCSV: LangChain LLM and Streamlit Interface


Welcome to ChatCSV, an interactive language-based application powered by LangChain LLM and Streamlit! This repository contains the code and resources for ChatCSV, where you can have engaging conversations with our language model.

## Prompt Engineering

Effective prompt engineering plays a crucial role in obtaining accurate and meaningful responses from the language model. Our team has carefully crafted prompts to provide context and guidance, resulting in coherent and informative text generation.

## Repository Structure

The repository is organized as follows:

- `interface.py`: The main Python file containing the Streamlit application code.
- `agent.py`: A Python file where LangChain LLM objects are created and managed.
- `requirements.txt`: A file listing the Python dependencies required to run the application.
- `README.md`: The Markdown file you are currently reading, providing an overview of the repository.

## Getting Started

To recreate the ChatCSV application locally, follow these steps:

1. Clone this GitHub repository to your local machine.
2. Make sure you have Python installed (recommended version is Python 3.7 or higher).
3. Install the required dependencies by running the following command:

   ```shell
   pip install -r requirements.txt

4. Create a .env file in the root directory of the project.
5. In the .env file, add the following line and replace "Your API Key" with your actual OpenAI API key:

    ```shell
   apikey = "Your API Key"

   This API key is required to access the LangChain LLM service.
6. Open the `agent.py` file and modify it according to your needs. This file is responsible for creating and managing LangChain LLM objects. You can customize it to define different language models or configurations.
7. Run the application using the following command:
    
    ```shell
   streamlit run interface.py

8. Access the application by opening your web browser and navigating to `http://localhost:8501`.


## Accessing the Hosted Application

You can also access ChatCSV through our hosted application at [https://chat-csv-b578fdb57380.herokuapp.com/](https://chat-csv-b578fdb57380.herokuapp.com/).

## Contributing

Contributions to this repository are welcome! If you have any ideas, bug fixes, or improvements, please feel free to submit a pull request.

## License

This repository is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code for both commercial and non-commercial purposes.

## Acknowledgments

We would like to express our gratitude to the developers and contributors of LangChain LLM and Streamlit for providing the tools and frameworks that make ChatCSV possible.

## Contact

If you have any questions or feedback, please don't hesitate to contact us at [saishmandavkar@live.com](mailto:saishmandavkar@live.com). We appreciate your interest and support!

Happy chatting with ChatCSV!
