# dj-technical-assignment-news-category

## News Category Semantic Search with Generative AI

### Overview

This project aims to develop a **semantic search system** using **Generative AI**, implementing a pipeline that includes:

- **Semantic Search**: Using embeddings to search news articles.
- **Generative AI**: Integrating LLMs for tasks such as summarization or question answering.
- **Scalable Expansion**: The system is designed to be extended to tasks like classification, recommendations, topic modeling, and more.

### Problem Definition

The goal of this project is to address the challenge of **semantic information retrieval in large volumes of news articles**. Using the **News Category Dataset**, we will implement an efficient and scalable search system that can also generate responses or summaries based on semantic relevance.

### Dataset

**News Category Dataset** from Kaggle:  
A dataset containing news articles categorized into various topics. It is suitable for **semantic search** or **classification** tasks.

- [Download the dataset](https://www.kaggle.com/datasets/rmisra/news-category-dataset)

### Approach

1. **Dataset Sourcing**:  
   - The **News Category Dataset** will be used to train the semantic search model.

2. **Preprocessing**:  
   - Cleaning, splitting, and transforming the data into a format compatible with embedding models.

3. **Modeling**:  
   - Generating embeddings using pre-trained models such as **Sentence Transformers**.
   - Integrating **MistralAL** for generative tasks like summarization and question answering.

4. **Search Pipeline**:  
   - **User input**: A semantic query.
   - **Initial retrieval**: Filters based on embeddings.
   - **Refinement**: Generating relevant responses or summaries using MistralAI.

5. **Evaluation**:  
   - The model will be evaluated based on:
     - **Precision** in search results.
     - **Quality** of generated summaries.
     - **Efficiency** in query response time.

### Installation

Follow these steps to set up the project locally:

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/dj-technical-assignment-news-category.git

2. Navigate to the project directory:
   ```bash
   cd dj-technical-assignment-news-category

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt

## Project Structure
```plaintext
dj-technical-assignment-news-category/
├── data/          # For datasets (add to .gitignore)
├── notebooks/     # For Jupyter Notebooks
├── src/           # Auxiliary scripts or functions
├── results/       # For visualizations or generated outputs
├── README.md      # Project documentation
└── requirements.txt # Project dependencies
```
## Possible Next Steps
- Integrate automatic classification based on embeddings.
- Add a basic user interface for querying.
- Implement topic modeling using techniques like LDA or embeddings.

## Contributions
Contributions are welcome. If you have suggestions or improvements, please create an issue or submit a pull request.

## License
This project is licensed under the MIT License. This means you are free to use, modify, and distribute the code, provided you include the original license notice in any copies or substantial portions of the code.
See the [LICENSE](LICENSE) file for more details.

## Contact
If you have any questions or need more information, feel free to reach out:
- **Email:** [nunezmartinezmalena@gmail.com](mailto:nunezmartinezmalena@gmail.com)  
- **LinkedIn:** [Malena Núñez Martínez](https://www.linkedin.com/in/malena-nunez-martinez/)
Thank you for your interest in this project!
