# TeamName_Innov8_3 – Final Submission
Team Name = Phoenix 
## Team Members

- Aditi Rathore 
- Devika Dudhaniya 
- Mythri Jadon 
- Harshita Rawat 

## Submission Contents

- `transcript.txt`  
  Contains transcripts for all sessions.  
  Format: Only lowercase alphabetical letters and spaces, no punctuation, numbers or special characters.  
  Each line begins with the original audio filename (e.g., file.mp3 : text).

- `submission.json`  
  Complete combined analysis for all subjects.  
  Strictly follows the official prescribed format.

- `Source_Code/`  
  Contains all Python scripts used for the solution:
    - `asrfinal.py` — Audio transcription using Whisper and formatting transcripts.
    - `truth_weaver_py.py` — Truth detection and labeling using LLM/API.
  Each file includes comments for execution instructions.

- `Bonus_Challenge/`  
  Contains bonus agentic flow documentation (`agentic_flow.json`, `agentic_flow.png`) and its own detailed README.

- `README.md`  
  This document, with instructions and requirements.

## How to Run the Code

### Environment Setup

- Recommended Python Version: **3.8+**
- (Optional) Use a virtual environment for isolation:
python -m venv venv
source venv/bin/activate # Linux/macOS
venv\Scripts\activate.bat # Windows

### Required Packages

Install dependencies with:

pip install torch transformers whisper spacy pandas huggingface_hub requests

If using Colab, also run:

pip install openai-whisper
sudo apt-get install ffmpeg

### Steps

1. **Transcription (`asrfinal.py`):**  
   - Converts audio files to text files with proper formatting.  
   - Produces `transcript.txt` as per guidelines.

2. **Truth Detection (`truth_weaver_py.py`):**  
   - Takes claims or transcripts and labels them as true/false/partial.  
   - Uses OpenRouter API/LLM; make sure API keys are configured.

3. **Submission JSON:**  
   - Ensure `submission.json` is generated and properly formatted before submission.

4. **Bonus Challenge:**  
   - Refer to `Bonus_Challenge/README.md` for agentic flow explanations and files.


## Important Notes

- Ensure `transcript.txt` and `submission.json` are present and correctly formatted per competition guidelines.  
- Only use the official evaluation set for generating and testing outputs.  
- All source scripts are commented for clarity and reproducibility.

Thank you for reviewing our submission!
