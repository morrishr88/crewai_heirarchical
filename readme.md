# Crew AI Router Retrieval / crewai_heirarchical

A concise, one-to-two sentence description of what the project does and why it is useful. 

## Table of Contents
1. [Features](#features)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [Contact](#contact)

## Features
* **Feature A:** This application retrieves local PDF and web data with OpenAI in Multi-Agent Environment with CrewAI.
* **Feature B:** CrewAI environment is composed of an orchestrator task (research_task), a pdf file retrieval agent (pdf_research_task) , and a web retrieval agent (web_research_task). 
* **Feature C:** The tasks are arranged in hierarchical structure with the research_task evaluating and routing queries to either the pdf task or web task. The results of the pdf tasks and web searchs are merges into a final report.

## Prerequisites
Before you begin, ensure you have met the following requirements:
* Python version       >= 3.10 and < 3.14 installed and the following python libraries
       langchain       ==1.4.3
       langchain-openai==1.6.7
       langgraph       ==1.2.12
       crewai          ==1.15.23
       [azure-ai-inference,litellm]
       tavily-python   ==0.8.4
       python-dotenv   ==1.2.4

* An active API key from AI LLM model that you manage or have access to.
* OS environment capable of running Bash or PowerShell scripts.

## Installation

To get a local copy up and running, follow these simple installation steps.

1. Clone the repository:
   ```bash
   git clone https://github.com/morrishr88/crewai_heirarchical
   ```
2. Navigate to the project directory:
   ```bash
   cd project-name
   ```
3. rename dot_env to .env
4. edit .env and update with correct application key.


## Usage

Provide examples of how to run the application or execute scripts. Include helpful code snippets.

```python
pip install "crewai>=1,<2" "requests>=2.32,<3" "python-dotenv>=1,<2" "python-dotenv>=1,<2" crewai_tools langchain langchain_community

# Initialize and run the application
open crewai_router_retriever.ipynb in a jupyter notebook environment 

#
Then execute the python blocks in order from top to bottom.

*For more detailed configuration options, refer to the project documentation.*

## Contributing

Contributions make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE.md` for more information.

## Contact

Your Name - harrypretzel88[@](https://twitter.com) - morrishrtz@yahoo.com