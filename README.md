# Intro

# References:

## AMI
Deep Learning OSS Nvidia Driver AMI GPU PyTorch 2.0.1 (Ubuntu 20.04) 20240312

## Setup:
Update and Upgrade
```bash
$ sudo apt update
# sudo apt upgrade -y
```

Install pip if required
```bash
$ sudo apt install pip
```

Install python virtualenv
```bash
$ pip install virtualenv
```

Clone this repo
```bash
$ git clone https://github.com/immu2able/pdfChatBot.git
$ cd pdfChatBot
```

Create the virtual env
```bash
$ python3 -m virutalenv env
```

Install project dependencies
```bash
$ pip install -r requirements.txt
```

Check if streamlit is installed and available and it should output the usage instructions/help message.
```bash
$ streamlit
```

Start the application and navigate to the [public_ip]:8501
```bash
$ streamlit run app.py
```

## CSV/JSON handling
https://www.neum.ai/post/llm-spreadsheets
