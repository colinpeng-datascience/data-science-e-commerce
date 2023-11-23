# Data Science in E-commerce

This repository contains sample code for data analysis work carried out as a data analyst in an e-commerce company.

## Models

### 1. Model Verify Pair (`verify_pair.ipynb`)

This Jupyter notebook showcases a model developed from scratch to determine if a keyword and a sentence are a match. The model employs two encoder Recurrent Neural Networks (RNNs), one for the keyword and another for the description. An Attention-like mechanism is integrated, concatenating the encoded keyword to every word of the sentence, ensuring the model remembers the keyword while processing the sentence.

**Document**: [Model Verify Pair Document](documents/verify_pair.pdf)

### 2. Model Keyword Extract (`keyword_extract.ipynb`)

This notebook illustrates a model designed for keyword extraction using a Seq2Seq neural network with an Attention mechanism.

**Document**: [Model Keyword Extract Document](documents/keyword_extract.pdf)

## Tech Stack

- **Programming Language**: Python
- **Libraries and Frameworks**: TensorFlow, PyTorch, Pandas, NumPy
- **Notebook Environment**: Jupyter Notebooks
- **Version Control**: Git

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo.git

2. Open and run the Jupyter notebooks:

- `model_verify_pair.ipynb`
- `model_keyword_extract.ipynb`

## License
This project is licensed under the MIT License

## Disclaimer
The code and documents in this repository are reproductions and generalizations of work conducted during a previous internship. The reproduction process involved creating original content outside of work hours and modifying the original work to ensure the removal of any proprietary or sensitive information related to the company. The intent is to showcase skills and knowledge gained during the internship without disclosing confidential or proprietary details.

Important Points:

- All reproductions and modifications were made with the utmost respect for intellectual property rights and adherence to any confidentiality or non-disclosure agreements signed during the internship.
- The content presented here is not an exact replica of the work done during the internship but has been altered to maintain anonymity and prevent the disclosure of proprietary information.
- This repository and its contents do not imply any endorsement or approval from the former employer, and the work presented here is solely intended for educational and portfolio demonstration purposes.
