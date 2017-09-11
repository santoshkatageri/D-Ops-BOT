# D-Ops-BOT - Jenkins plugin for ErrBOT

D-Ops-BOT is a plugin for [Err](https://github.com/gbin/err) that allows you to interact with [Jenkins](http://jenkins-ci.org), a continuous integration tool. 
and This plugin is based on the original work by [benvd](https://github.com/benvd/err-jenkins) with some modifications 

## Features

* Support Jenkins 2.x!
* Search / List available jobs.
* List parameters for a given job.
* Enable, Disabled and Delete job.
* Build jobs with or without parameters.
* Webhook support! Receive REST calls on build success/failure

## Usage

### Requirements

This plugin is tested against Python 2.7+ and 3.3+. It depends on the `python-jenkins` and `validators` packages and IT is based on errbot.

steps To install errbot: 

Install errbot from pip
Initialize the directory
Install errbot from pip or from [Err](ttps://github.com/errbotio/errbot) and Change the config.py file with your details
Make a directory somewhere (here called errbot) to host Errbot's data files
Initialize the directory

.. code:: bash

    $ pip install errbot
    $ mkdir errbot; cd errbot
    $ errbot --init
    $ errbot

Adding support for a slack chat system

$ pip install "errbot[slack]" 


In order to configure Errbot to connect to slack chat systems you'll need to tweak the `config.py` file generated
by `errbot --init`.

## Configuration

You can set some default configuration values in your Errbot's `config.py`:

```python
# Main configuration
JENKINS_URL = 'http://JenkinsURL'  # Must begins with 'http' or 'https'.
JENKINS_USERNAME = 'myuser'  # Make sure Jenkins ACL is configured.
JENKINS_PASSWORD = 'mypassword'  # Use a password or token.

.. code:: bash
	$ pip install python-jenkins validators



### Installation of OpsGenie

Install 

```
!repos install https://github.com/santoshpkatageri/D-Ops-BOT
```

### Commands

Use `!help DOpsBOT` to see the available commands and their explanation.



