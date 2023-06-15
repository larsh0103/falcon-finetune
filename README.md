# Falcon Language Learning Model (LLM) Fine-tuning 🚀🧑‍💻🦅

Welcome to our open-source repository! This project focuses on fine-tuning the Falcon Language Learning Model (LLM) on a custom dataset, enabling the model to generate dialogues based on specific prompts in various languages and contexts. We use Norwegian as an example. You can find the original Falcon LLM [here](https://falconllm.tii.ae/).

The repo consists of two notebooks: 

1. `generate_dataset.ipynb` - This notebook includes code for creating a dataset consisting of dialogues. It is focused on making the dataset reflect a diverse set of characters and scenarios.

2. `fine_tuning.ipynb` - This notebook walks you through the process of fine-tuning the Falcon LLM on your custom dataset. It includes the entire process, starting from converting the dataset into the Hugging Face format to running the fine-tuning. 

## Getting Started 🏁

### Prerequisites
- You should have Python 3.8+ installed on your system.
- Install [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) to manage your Python environment and install dependencies.

### Setup Instructions 🛠️
1. **Clone the repository** by running `git clone https://github.com/yourusername/falcon-llm-finetuning.git` on your local machine. 

2. **Navigate into the cloned repository** using the command `cd falcon-llm-finetuning`.

3. **Set up the Python environment** by creating a new Conda environment using the provided `environment.yaml` file. Use the command `conda env create -f environment.yaml`. This will create a new Conda environment named `falcon-llm`.

4. **Activate the Conda environment** with the command `conda activate falcon-llm`. 

5. **Start Jupyter Notebook** using the command `jupyter notebook`.

You can now navigate the notebooks in your browser!

## Contribution 🤝
We welcome contributions from everyone. Feel free to open an issue or submit a pull request if you find any bugs or have some suggestions for improvements. 

## Contact 📧
If you have any questions or need further clarification, feel free to reach out to me.

Happy fine-tuning! 🎉