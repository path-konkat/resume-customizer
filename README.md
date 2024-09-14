# Resume Customization App
Streamline your job search with this LLM-based application that generates a customized resume and cover letter based on a job description input

## DESCRIPTION
This repository contains python script for an application that uses local LLM (ollama) to generate customized versions of your resume and cover letter based on a job description submitted via the user interface. It does this by accessing an exisiting collection of past resumes and cover letters on which to build a new version customized for the role and company described.

## DEPENDENCIES
* ollama (model 'phi3:mini') _(see [ollama documentation](https://ollama.com/) and [model documentation](https://ollama.com/library/phi3))_
* chromadb _(see [documentation](https://docs.trychroma.com/getting-started))_
* streamlit _(see [documentation](https://docs.streamlit.io/get-started/installation))_
* docker _(optional, see [documentation](https://www.docker.com/get-started/))_

## INSTRUCTIONS
To run application:
1. Customize for your use
    *   Fork this repository 
    *   Open [resume_customizer_app.py](resume_customizer_app.py) script and update filepath to folders containing resumes and cover letters. 
2. Launch ollama server 
    * Open command line interface
    * Run the `ollama serve` command
    * Minimize and allow to run in background
3. Launch the user interface
    * Open new command line interface window
    * Navigate to directory contain this repository
    * Run the `streamlit run resume_customizer_app.py` command to launch the user interface


## ATTRIBUTION
[Jamie Bond](https:www.github.com/jbondai), Managing Principal  
[path.konkat, LLC](https://www.pathkonkat.com) | info@pathkonkat.com

