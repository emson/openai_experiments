# OpenAI Experiments

## Requirements

Python 3.7.5
Git
ffmpeg - for random_agent.py

## Instructions

Open the Windows Command Prompt:

1. In the "Run" box (that says 'Type here to search') at the bottom of the screen type: command
2. Click on the Command Prompt App

You should have a black command prompt screen. Let's create a new directory for the stem project, and move into that directory.
In the command prompt type:

    mkdir c:\%homepath%\stem
    cd c:\%homepath%\stem




## Setup

Start a virturl environement:

    python -m venv venv
    
On Windows activate Python:

    venv\Scripts\activate.bat

Now upgrade `pip` to the latest version:

     pip install --upgrade pip

Now install the project (gym) code:

    pip install -r requirements.txt



## Manual Install

    git clone https://github.com/openai/gym
    cd gym
    pip install wheel
    pip install -e .
    pip install 'gym[atari]'


## Install

    pip install -r requirements.txt


