# RoshanEssayEdu
In order to validate essays, it uses the copyleaks API to check for plagiarism. It also uses a modified version of GPT-2 to detect the likelihood that the text was real or fake. Then it outputs a validation score using these 2 scores. In order to grade the essay, it uses a neural network model trained on the automatic essay grading dataset on Kaggle found here https://www.kaggle.com/c/asap-aes/data .Take this code and go build a profitable startup with it.

This is an ongoing, open source project. Please contribute so this project can be finished faster. 
Quickstart
       Install dependencies for Python >3.6 :

       pip install -r requirements.txt
       run server for gpt-2-small:
       python server.py

server.py options
           usage: server.py [-h] [--model MODEL] [--nodebug NODEBUG] [--address ADDRESS]
                 [--port PORT] [--nocache NOCACHE] [--dir DIR] [--no_cors]

optional arguments:
               -h, --help         show this help message and exit
               --model MODEL		 choose either 'gpt-2-small' (default) or 'BERT' or your own
                --nodebug NODEBUG  server in non-debugging mode
                  --port PORT	     port to launch UI and API (default:5001)
                 --no_cors          launch API without CORS support (default: False)
