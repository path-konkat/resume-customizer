# Resume Customization App
LLM-based application that will generate a customized resume and cover letter based on a job description input

## DESCRIPTION
This repository contains python script for an application that returns a customized resume and cover letter for a job description submitted via the user interface. Using an LLM and your collection of past resumes and cover letters, the application 

## DEPENDENCIES
* ollama (model 'phi3:mini') _(see [ollama documentation](https://ollama.com/) and [model documentation](https://ollama.com/library/phi3))_
* chromadb _(see [documentation](https://docs.trychroma.com/getting-started))_
* streamlit _(see [documentation](https://docs.streamlit.io/get-started/installation))_
* docker _(optional, see [documentation](https://www.docker.com/get-started/))_

## INSTRUCTIONS
To run application:
1. Customize script for your use
    *   Fork this repository 
    *   Open [resume_customizer_app.py](resume_customizer_app.py) script and update filepath to folders containing resumes and cover letters. 
2. Launch ollama server. 
    * Open command line interface
    * Run the `ollama serve` command
    * Minimize and allow to run in background
3. Launch the app interface
    * Open new command line interface window
    * Navigate to directory contain this repository
    * Run the `streamlit run resume_customizer_app.py` command to launch the UI


## ATTRIBUTION
* path.konkat, LLC | [www.pathkonkat/com](https://www.pathkonkat.com) | info@pathkonkat.com
* Developer: [Jamie Bond](https:www.github.com/jbondai), Managing Principal | [path.konkat](https://www.pathkonkat.com)

