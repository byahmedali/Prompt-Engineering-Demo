# Prompt Engineering Demo
This repository includes a simple notebook to demonstrate prompt engineering principles. It contains explanations, code examples (zero-shot and few-shot), tips on *task, context, examples, role, format, tone*, and guidance for using chain-of-thought (CoT) techniques.

## Prerequisites
- Python 3.13
- [GROQ API Key](https://console.groq.com/keys)

## Setup
1. **Clone this repository:**
```
git clone https://github.com/byahmedali/Prompt-Engineering-Guide.git
cd Prompt-Engineering-Guide
```

2. **Create and activate a virtual environment:**
```
py -3.13 -m venv venv
# On Windows
.\venv\Scripts\activate

# On Unix or MacOS
source venv/bin/activate
```

3. **Install dependencies:**
```
pip install -r requirements.txt
```

4. **Create a `.env` file in the root directory and add your GROQ API key:**
```
GROQ_API_KEY=your_groq_api_key
```

#### If you are going to run notebooks in Jupyter:
5. **Add your virtual environment to Jupyter as a new kernel:**
```
python -m ipykernel install --user --name=venv --display-name "Prompt Engineering"
```

6. **Launch the local Jupyter Notebook server, and make sure to open & run notebooks using `Prompt Engineering` kernel:**
```
jupyter notebook
```
Now your can run the [Prompt Engineering Guide](./Prompt%20Engineering%20Guide.ipynb) notebook.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.