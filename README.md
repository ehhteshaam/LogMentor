# LogMentor
The Generative AI-powered Log Analyzer accelerates production incident debugging for support developers by swiftly analyzing raw log files, providing comprehensive root cause analysis, and suggesting effective remediation strategies. Its versatility makes it a natural fit within the IT support workflow of any organization. Additionally, it seamlessly integrates with popular IT operations management tools such as ServiceNow, serving as a powerful plugin to enhance incident resolution efficiency. With an estimated efficacy of **95% cost reduction** and **90% time reduction** in IT incident resolution, its impact is significant.

🚀 **Live App:** [LogMentor Live on Streamlit](https://logmentor.streamlit.app)

## Prerequisites

**Cloud Services:** AWS Bedrock or AWS Sagemaker and AWS Cloud9  
**Interpreter:** Python3  
**Libraries:** boto3, LangChain, Streamlit

## Steps to Run

1. Clone the repository: `git clone https://github.com/ehhteshaam/LogMentor.git`
2. Go to the directory: `cd LogMentor`
3. Create a new virtual environment, activate and install required libraries:
   - `python -m venv venv`
   - On Windows: `.\venv\Scripts\activate`
   - On macOS/Linux: `source venv/bin/activate`
   - `pip install -r requirements.txt`
4. Installing AWS prerequisites: `python OneTimeExecution.py`
5. Initiate the app: `streamlit run streamlitUI.py`

## Landing Page
![image](https://github.com/ehhteshaam/LogMentor/blob/main/assets/LogMentor.png)
