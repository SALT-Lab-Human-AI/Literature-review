## Usage

To run the code, you need to 1) create a PDF parsing server and run in the background, 2) create the LLM feedback server, 3) open the web browser and upload your paper.

### Create and Run PDF Parsing Server

⚠️⚠️⚠️ **ScienceBeam PDF parser only supports x86 Linux operating system. Please let us know if you find solutions for other operating systems!**

```bash
conda env create -f conda_environment.yml
conda activate ScienceBeam
python -m sciencebeam_parser.service.server --port=8080  # Make sure this is running in the background
```

### Create and Run LLM Feedback Server

```bash
conda create -n llm python=3.10
conda activate llm
pip install -r requirements.txt
cat YOUR_OPENAI_API_KEY > key.txt  # Replace YOUR_OPENAI_API_KEY with your OpenAI API key starting with "sk-"
python main.py  # If you have installed ScienceBeam using x86 Linux and want to generate feedback from the raw PDF file
python main_from_text.py  # If you are using other operating systems or want to generate feedback from the parsed paper in text format
```

### Open the Web Browser and Upload Your Paper

Open http://0.0.0.0:7799 and upload your paper. The feedback will be generated in around 120 seconds.

