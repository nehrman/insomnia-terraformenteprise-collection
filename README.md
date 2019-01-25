# Insomnia Collection For Terraform Enterprise

This repo hosts an export of my API Request collection to manipulate Terraform Enterprise from its API and provides some examples.

## Pre Requisites

You must have Insomnia client installed on your OS.
If not, you can find it here : https://insomnia.rest/download/

## How to use it 

Just do an import from Insomnia GUI and configure environment variables :

- Base environment :

```
  "TFE_ADDR": "", 
  "TFE_OAUTH_CLIENT": "",
  "TFE_OAUTH_TOKEN": "",
  "TFE_ORG": "",
  "TFE_TOKEN": ""
```

- For Each environment that you want to use :

```
  "TFE_REPO_BRANCH": "",
  "TFE_REPO_DEFAULT_BRANCH": "",
  "TFE_REPO_DIRECTORY": "",
  "TFE_WORKSPACE_NAME": ""
```

## Authors

* **Nicolas Ehrman** - *Initial work* - [Hashicorp](https://www.hashicorp.com)

