# RAG-Multimodal-Cohere

A RAG (Retrieval-Augmented Generation) architecture utilizing Cohere's Embed-4 model to generate multimodal embeddings of image and PDF data, with question answering powered by Google's efficient Gemini 2.5 Flash model.

## 🌟 Features

- 📄 PDF document processing and analysis
- 🖼️ Image processing and understanding
- 🔍 Multimodal embeddings using Cohere's Embed-4
- 💡 Intelligent question answering with Google's Gemini 2.5 Flash
- 🚀 Streamlit-based interactive web interface
- 📊 Real-time document and image analysis

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/RAG-Multimodal-Cohere.git
cd RAG-Multimodal-Cohere
```

2. Create and activate a virtual environment:
```bash
python3.12 -m venv myenv
source myenv/bin/activate  # On Windows, use: myenv\Scripts\activate
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

## 🔑 API Keys Setup

This project requires API keys from:
- Cohere (for embeddings)
- Google AI (for Gemini model)

Create a `.env` file in the project root and add your API keys:
```env
COHERE_API_KEY=your_cohere_api_key
GOOGLE_API_KEY=your_google_api_key
```

## 🚀 Usage

1. Start the Streamlit application:
```bash
streamlit run app.py
```

2. Open your web browser and navigate to `http://localhost:8501`

3. Upload PDF documents or images and start asking questions!

## 🏗️ Architecture

The application follows a RAG architecture:
1. **Document Processing**: Handles PDF and image inputs
2. **Embedding Generation**: Uses Cohere's Embed-4 for multimodal embeddings
3. **Retrieval**: Finds relevant context based on user queries
4. **Generation**: Utilizes Gemini 2.5 Flash for accurate responses

## 📋 Requirements

- Python 3.12+
- Streamlit >= 1.32.0
- Cohere >= 5.0.0
- Google Generative AI >= 0.3.0
- Other dependencies listed in `requirements.txt`

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📬 Contact

For questions and feedback, please open an issue in the GitHub repository.

## 🙏 Acknowledgments

- Cohere for their Embed-4 model
- Google for the Gemini 2.5 Flash model
- The Streamlit team for their amazing framework