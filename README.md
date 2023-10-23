# pp_laba_back
Using python 3.8.0 and virualenv in PyCharm to deploy a server

## Contents

* [Environment requirements](#Environment-requirements)
* [Cloning a repository](#Cloning-a-repository)
* [Launch the server](#Launch-the-server)

## Environment requirements

First of all, we need a PyCharm. To deploy a server we need to install several libs.

* `Flask` - by running this command in terminal * `python -m pip install Flask`
* `waitress` - by running this command in terminal * `python -m pip install waitress`


## Cloning a repository

Run this command - * `git clone https://github.com/mililiana/pp_laba_back.git`

## Launch the server

Part of our development flow allows for staging servers. If you wish to test your work on the staging servers then the below flow is for you.

* Run this  ` cd .\pp_laba_back\ `
* Then this `waitress-serve --host 127.0.0.1 main:app`

After this you`ll get a server
