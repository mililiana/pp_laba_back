# pp_laba_back
Using python 3.8.0 and virtualenv in PyCharm to deploy a server

## Contents
* [Cloning a repository](#Cloning-a-repository)
* [Environment requirements](#Environment-requirements)
* [Launch the server](#Launch-the-server)

## Cloning a repository

Run this command - * `git clone https://github.com/mililiana/pp_laba_back.git`

## Environment requirements

To install the packages according to the configuration file `requirements.txt` use this command below

*`pip install -r requirements.txt`


## Launch the server

Part of our development flow allows for staging servers. If you wish to test your work on the staging servers then the below flow is for you.

* Run this  ` cd .\pp_laba_back\ `
* Then this `waitress-serve --host 127.0.0.1 main:app`

After this you`ll get a server
