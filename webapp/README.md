# Environmental variables 
CC_PRE_RUN_HOOK="git clone https://github.com/RamiMohammedSeid/OpenNMT-py; cd OpenNMT-py; pip install -r requirements.opt.txt;cd ..;git clone https://github.com/RamiMohammedSeid/HornMorpho/; cd HornMorpho;cd HornMorpho; python setup.py install;cd .."
CC_PYTHON_BACKEND="gunicorn"
CC_PYTHON_MODULE="app:app"
CC_PYTHON_VERSION="3.6"
ENABLE_GZIP_COMPRESSION="false"
GUNICORN_WORKER_CLASS="aiohttp.GunicornWebWorker"
PORT="8080"
# upload to clevercloud or download AIOhttp
