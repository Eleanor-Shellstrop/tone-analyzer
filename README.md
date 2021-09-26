# Tone Analyzer with IBM's Watson

This is an exericese to play with Watson, Jupyter Notebook and using Python. 

Note: I had to turn off my VPN to navigate and create an account on IBM's website. 

## IBM Description

The IBM Watson™ Tone Analyzer service uses linguistic analysis to detect emotional and language tones in written text. The service can analyze tone at both the document and sentence levels. You can use the service to understand how your written communications are perceived and then to improve the tone of your communications. Businesses can use the service to learn the tone of their customers' communications and to respond to each customer appropriately, or to understand and improve their customer conversations. [source](https://cloud.ibm.com/apidocs/tone-analyzer)

## Instructions

### Download libraries and make an IBM Cloud account

If you do not have Python, Jupyter Notebook or an IBM Cloud account:

1. Install Juptyer Notebook or Anaconda
    * [Install Python, or see Anaconda below](https://www.python.org/downloads/)
    * [Install Jupyter Notebook](https://jupyter.readthedocs.io/en/latest/content-quickstart.html)
    * [Install Anaconda, which includes Jupyter Notebook and Python](https://docs.anaconda.com/anaconda/install/index.html)
2. Sign in or Create an IBM account (free tier is fine).
    * [Create account here](https://cloud.ibm.com/registration?target=/catalog/services/discovery?hideTours=true&&cm_sp=WatsonPlatform-WatsonPlatform-_-OnPageNavCTA-IBMWatson_Discovery-_-Watson_Developer_Website)

### Running the Program 
1. Clone the repository
2. On the IBM website, retrieve your API key and URL for the variables in "Authenticate."
    * Find the Tone Analyzer product and click "Create."
    * Click the "Manage" tab.
    * Copy and paste your API key and URL values in the variables, in single or double quotes. 
    * Do not share your API key with anyone else or upload to any public repository. 

    Note: I had saved my variable to my local environment and used the `.get` method to retrive them.
    If you do not plan to share your repo and want to **only run locally**, you can plug in your variables with the syntax:

    ```python
    url = 'YOUR URL HERE'
    apikey = 'YOUR API KEY HERE'
    ```
3. Open Jupyter Notebook from the command line with `jupyter notebook`. 
4. Open the repository from within Jupyter Notebook.
5. Run all the code cells. 

## Making Changes

Edit the text fields and run again to see your new analysis. 