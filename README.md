# UETGuide-Chatbot


---

# UETGuide Chatbot

UETGuide Chatbot is an AI-powered question-answering system designed to help users navigate information about the University of Engineering and Technology (UET). Built using Langchain, RAG (Retrieval-Augmented Generation), Qdrant vector database, Hugging Face Embeddings, and Gradio, UETGuide provides a seamless and interactive UI for users to explore university-related content.

## Features
- **Natural Language Processing**: Uses RAG to process and respond to user queries.
- **Efficient Information Retrieval**: Leverages Qdrant vector database for high-speed and accurate retrieval of relevant information.
- **Interactive User Interface**: Gradio provides a responsive and accessible UI for users to interact with the chatbot.

## Technologies Used
- **Langchain**: Framework for building LLM applications.
- **RAG (Retrieval-Augmented Generation)**: Model for generating responses based on retrieved data.
- **Qdrant**: Vector database for storing and retrieving embeddings.
- **Hugging Face Embeddings**: Embedding models from Hugging Face for accurate and efficient data processing.
- **Gradio**: Library for creating interactive UIs with minimal code.

## Installation
1. **Clone the repository**:
    ```bash
    git clone <your-repo-url>
    cd UETGuideChatbot
    ```

2. **Install required packages**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up Qdrant Vector Database**:
   - Follow [Qdrant’s setup guide](https://qdrant.tech/documentation/) to configure the database.
   - Ensure API endpoints and access keys are correctly set in your environment variables or configuration file.

4. **Run the Application**:
    ```bash
    python app.py
    ```



## Usage
- Once running, the Gradio UI will load the chatbot interface. Users can input questions related to UET, and the chatbot will generate responses based on available data.

## Demo Video
Check out a demo of the chatbot in action below:
https://youtu.be/xWeDDBV8SpY






## Future Enhancements
- **Extended Database**: Integrate additional university resources to improve knowledge coverage.
- **Deployment on Cloud**: Deploy the chatbot on Hugging Face Spaces or another cloud platform for broader accessibility.

## Contributing
Feel free to open issues or contribute to improve UETGuide Chatbot!

## License
This project is licensed under the MIT License.

