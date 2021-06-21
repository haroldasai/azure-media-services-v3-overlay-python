## Getting Started

### Prerequisites

* Install Python 3.x
* Install the Python SDKs
**pip3 install azure-mgmt-resource
**pip3 install azure-mgmt-media==3.0.0
**pip3 install azure-identity
**pip3 install azure-storage-blob
**pip3 install adal

### Set following environment variables so that this python program can use them to connect to your Azure Media Service Account

AADCLIENTID="00000000-0000-0000-0000-000000000000"
AADSECRET="00000000-0000-0000-0000-000000000000"
AADTENANTDOMAIN="microsoft.onmicrosoft.com"
AADTENANTID="00000000-0000-0000-0000-000000000000"
ACCOUNTNAME="amsaccount"
LOCATION="West US 2"
RESOURCEGROUP="amsResourceGroup"
SUBSCRIPTIONID="00000000-0000-0000-0000-000000000000"
ARMAADAUDIENCE="https://management.core.windows.net/"
ARMENDPOINT="https://management.azure.com/"

STORAGEACCOUNTNAME="XXXXX"
STORAGEACCOUNTKEY="XXXXX"

### Execute

Go to project directory and run 
>python overlay-encoding.py
Getting .env values
Creating AMS client
Creating input asset inputassetName8374
Creating input asset inputlogoassetName8374
Creating output asset outputassetName8374
Uploading the file sample_beach.mp4
Uploading the file cloud.png
Creating transform MyOverlayTransform18374
Creating  overlay job MyOvarlayJob8374
First job check
Processing
Processing
Processing
Finished

After it finishes, you should be able to see input image asset, input logo asset, and output Overlayed video assest that is ready to be streamed. 