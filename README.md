## Azure ML - MLOps demos

* [How to train your model locally](code/train%20locally/)
* [How to train your model remotely using Azure ML compute](code/train%20remotely/)
* [E2E MLOps pipeline](code/mlops%20e2e/)

## Requirements
- VsCode
- Python 3.7
- A virtual environment tool (venv)
- An Azure account 
- An Azure ML workspace

## Preparation

### VsCode
* Install [Visual Studio Code](https://code.visualstudio.com/)

### Python
* Install [Python 3.7](https://www.python.org/downloads/release/python-31011/)

### Python3 Virtualenv Setup
*  Installation
        To install virtualenv via pip run:
            $ pip3 install virtualenv
* Creation of virtualenv:
    - Windows
    $ python -m virtualenv venv (in the openAI workshop directory)
    - Mac
    $ virtualenv -p python3 <desired-path>

    Activate the virtualenv:
    $ source <desired-path>/bin/activate

    Deactivate the virtualenv:
    $ deactivate

#### Python3 Virtualenv Setup
*  Installation
        To install virtualenv via pip run:
            $ pip3 install virtualenv
* Creation of virtualenv:
    - Windows
    $ python -m virtualenv venv (in the openAI workshop directory)
    - Mac
    $ virtualenv -p python3 <desired-path>

### Install all libraries in your virtual environment
* Activate the environment
    Windows:
        .\venv\Scripts\activate.ps1
    Mac:
    $ source ./venv/bin/activate

* Make sure you have the requirements installed in your Python environment using `pip install -r requirements.txt`.

# IMPORTANT!
### Setup environment variables
* Rename the '.env.template' file to '.env' and modify as follows:
```
SUBSCRIPTION_ID = "<azure subscription id here>"
RESOURCE_GROUP = "<resource group>"
AML_WORKSPACE_NAME = "<azure ml worskpace name>"
```
Save the .env file
