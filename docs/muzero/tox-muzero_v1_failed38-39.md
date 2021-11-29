muzero37 create: /home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/.tox/muzero37
muzero37 installdeps: -r/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/requirements.txt
muzero37 installed: absl-py==1.0.0,ale-py==0.7.3,anyio==3.4.0,argcomplete==1.12.3,argon2-cffi==21.1.0,astor==0.8.1,attrs==21.2.0,Babel==2.9.1,backcall==0.2.0,bleach==4.1.0,cached-property==1.5.2,cachetools==4.2.4,certifi==2021.10.8,cffi==1.15.0,charset-normalizer==2.0.7,cloudpickle==2.0.0,cycler==0.11.0,debugpy==1.5.1,decorator==5.1.0,defusedxml==0.7.1,entrypoints==0.3,fonttools==4.28.2,gast==0.2.2,google-auth==1.35.0,google-auth-oauthlib==0.4.6,google-pasta==0.2.0,grpcio==1.42.0,gym==0.21.0,h5py==3.6.0,idna==3.3,importlib-metadata==4.8.2,importlib-resources==5.4.0,ipykernel==6.4.1,ipython==7.29.0,ipython-genutils==0.2.0,jedi==0.18.1,Jinja2==3.0.3,json5==0.9.6,jsonschema==4.2.1,jupyter-client==7.1.0,jupyter-core==4.9.1,jupyter-server==1.12.0,jupyterlab==3.2.0,jupyterlab-pygments==0.1.2,jupyterlab-server==2.8.2,Keras==2.3.1,Keras-Applications==1.0.8,Keras-Preprocessing==1.1.2,kiwisolver==1.3.2,Markdown==3.3.6,MarkupSafe==2.0.1,matplotlib==3.5.0,matplotlib-inline==0.1.3,mistune==0.8.4,nbclassic==0.3.4,nbclient==0.5.9,nbconvert==6.3.0,nbformat==5.1.3,nest-asyncio==1.5.1,notebook==6.4.6,numpy==1.21.4,oauthlib==3.1.1,opencv-python==4.5.4.60,opt-einsum==3.3.0,packaging==21.3,pandas==1.3.4,pandocfilters==1.5.0,parso==0.8.2,pexpect==4.8.0,pickleshare==0.7.5,Pillow==8.4.0,plotly==5.3.1,prometheus-client==0.12.0,prompt-toolkit==3.0.22,protobuf==3.19.1,ptyprocess==0.7.0,pyasn1==0.4.8,pyasn1-modules==0.2.8,pycparser==2.21,Pygments==2.10.0,pyparsing==3.0.6,pyrsistent==0.18.0,python-dateutil==2.8.2,pytz==2021.3,PyYAML==6.0,pyzmq==22.3.0,requests==2.26.0,requests-oauthlib==1.3.0,rsa==4.7.2,scipy==1.4.1,seaborn==0.11.2,Send2Trash==1.8.0,setuptools-scm==6.3.2,six==1.16.0,sniffio==1.2.0,tenacity==8.0.1,tensorboard==2.1.1,tensorflow==2.1.0,tensorflow-estimator==2.1.0,termcolor==1.1.0,terminado==0.12.1,testpath==0.5.0,tomli==1.2.2,tornado==6.1,tqdm==4.62.3,traitlets==5.1.1,typing_extensions==4.0.0,urllib3==1.26.7,wcwidth==0.2.5,webencodings==0.5.1,websocket-client==1.2.1,Werkzeug==2.0.2,wrapt==1.13.3,zipp==3.6.0
muzero37 run-test-pre: PYTHONHASHSEED='1198970330'
muzero37 run-test: commands[0] | python -c 'print((80*"=")+"\n"+"python3.7_testenv:muzero"+"\n"+(80*"="))'
================================================================================
python3.7_testenv:muzero
================================================================================
muzero37 run-test: commands[1] | python -c 'print((80*"~")+"\n"+"pip install --upgrade pip setuptools wheel"+"\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip install --upgrade pip setuptools wheel
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
muzero37 run-test: commands[2] | pip install --upgrade pip
Requirement already satisfied: pip in ./.tox/muzero37/lib/python3.7/site-packages (21.3.1)
muzero37 run-test: commands[3] | pip install --upgrade setuptools
Requirement already satisfied: setuptools in ./.tox/muzero37/lib/python3.7/site-packages (58.3.0)
Collecting setuptools
  Using cached setuptools-59.2.0-py3-none-any.whl (952 kB)
Installing collected packages: setuptools
  Attempting uninstall: setuptools
    Found existing installation: setuptools 58.3.0
    Uninstalling setuptools-58.3.0:
      Successfully uninstalled setuptools-58.3.0
Successfully installed setuptools-59.2.0
muzero37 run-test: commands[4] | pip install --upgrade wheel
Requirement already satisfied: wheel in ./.tox/muzero37/lib/python3.7/site-packages (0.37.0)
muzero37 run-test: commands[5] | python -c 'print((80*"~")+"\n"+"python -m pip list --format=columns"+"\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
python -m pip list --format=columns
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
muzero37 run-test: commands[6] | python -m pip list --format=columns
Package              Version
-------------------- ---------
absl-py              1.0.0
ale-py               0.7.3
anyio                3.4.0
argcomplete          1.12.3
argon2-cffi          21.1.0
astor                0.8.1
attrs                21.2.0
Babel                2.9.1
backcall             0.2.0
bleach               4.1.0
cached-property      1.5.2
cachetools           4.2.4
certifi              2021.10.8
cffi                 1.15.0
charset-normalizer   2.0.7
cloudpickle          2.0.0
cycler               0.11.0
debugpy              1.5.1
decorator            5.1.0
defusedxml           0.7.1
entrypoints          0.3
fonttools            4.28.2
gast                 0.2.2
google-auth          1.35.0
google-auth-oauthlib 0.4.6
google-pasta         0.2.0
grpcio               1.42.0
gym                  0.21.0
h5py                 3.6.0
idna                 3.3
importlib-metadata   4.8.2
importlib-resources  5.4.0
ipykernel            6.4.1
ipython              7.29.0
ipython-genutils     0.2.0
jedi                 0.18.1
Jinja2               3.0.3
json5                0.9.6
jsonschema           4.2.1
jupyter-client       7.1.0
jupyter-core         4.9.1
jupyter-server       1.12.0
jupyterlab           3.2.0
jupyterlab-pygments  0.1.2
jupyterlab-server    2.8.2
Keras                2.3.1
Keras-Applications   1.0.8
Keras-Preprocessing  1.1.2
kiwisolver           1.3.2
Markdown             3.3.6
MarkupSafe           2.0.1
matplotlib           3.5.0
matplotlib-inline    0.1.3
mistune              0.8.4
nbclassic            0.3.4
nbclient             0.5.9
nbconvert            6.3.0
nbformat             5.1.3
nest-asyncio         1.5.1
notebook             6.4.6
numpy                1.21.4
oauthlib             3.1.1
opencv-python        4.5.4.60
opt-einsum           3.3.0
packaging            21.3
pandas               1.3.4
pandocfilters        1.5.0
parso                0.8.2
pexpect              4.8.0
pickleshare          0.7.5
Pillow               8.4.0
pip                  21.3.1
plotly               5.3.1
prometheus-client    0.12.0
prompt-toolkit       3.0.22
protobuf             3.19.1
ptyprocess           0.7.0
pyasn1               0.4.8
pyasn1-modules       0.2.8
pycparser            2.21
Pygments             2.10.0
pyparsing            3.0.6
pyrsistent           0.18.0
python-dateutil      2.8.2
pytz                 2021.3
PyYAML               6.0
pyzmq                22.3.0
requests             2.26.0
requests-oauthlib    1.3.0
rsa                  4.7.2
scipy                1.4.1
seaborn              0.11.2
Send2Trash           1.8.0
setuptools           59.2.0
setuptools-scm       6.3.2
six                  1.16.0
sniffio              1.2.0
tenacity             8.0.1
tensorboard          2.1.1
tensorflow           2.1.0
tensorflow-estimator 2.1.0
termcolor            1.1.0
terminado            0.12.1
testpath             0.5.0
tomli                1.2.2
tornado              6.1
tqdm                 4.62.3
traitlets            5.1.1
typing_extensions    4.0.0
urllib3              1.26.7
wcwidth              0.2.5
webencodings         0.5.1
websocket-client     1.2.1
Werkzeug             2.0.2
wheel                0.37.0
wrapt                1.13.3
zipp                 3.6.0
muzero37 run-test: commands[7] | python -c 'print((80*"~")+"\n"+"pip freeze\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip freeze
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
muzero37 run-test: commands[8] | pip freeze
absl-py==1.0.0
ale-py==0.7.3
anyio==3.4.0
argcomplete==1.12.3
argon2-cffi==21.1.0
astor==0.8.1
attrs==21.2.0
Babel==2.9.1
backcall==0.2.0
bleach==4.1.0
cached-property==1.5.2
cachetools==4.2.4
certifi==2021.10.8
cffi==1.15.0
charset-normalizer==2.0.7
cloudpickle==2.0.0
cycler==0.11.0
debugpy==1.5.1
decorator==5.1.0
defusedxml==0.7.1
entrypoints==0.3
fonttools==4.28.2
gast==0.2.2
google-auth==1.35.0
google-auth-oauthlib==0.4.6
google-pasta==0.2.0
grpcio==1.42.0
gym==0.21.0
h5py==3.6.0
idna==3.3
importlib-metadata==4.8.2
importlib-resources==5.4.0
ipykernel==6.4.1
ipython==7.29.0
ipython-genutils==0.2.0
jedi==0.18.1
Jinja2==3.0.3
json5==0.9.6
jsonschema==4.2.1
jupyter-client==7.1.0
jupyter-core==4.9.1
jupyter-server==1.12.0
jupyterlab==3.2.0
jupyterlab-pygments==0.1.2
jupyterlab-server==2.8.2
Keras==2.3.1
Keras-Applications==1.0.8
Keras-Preprocessing==1.1.2
kiwisolver==1.3.2
Markdown==3.3.6
MarkupSafe==2.0.1
matplotlib==3.5.0
matplotlib-inline==0.1.3
mistune==0.8.4
nbclassic==0.3.4
nbclient==0.5.9
nbconvert==6.3.0
nbformat==5.1.3
nest-asyncio==1.5.1
notebook==6.4.6
numpy==1.21.4
oauthlib==3.1.1
opencv-python==4.5.4.60
opt-einsum==3.3.0
packaging==21.3
pandas==1.3.4
pandocfilters==1.5.0
parso==0.8.2
pexpect==4.8.0
pickleshare==0.7.5
Pillow==8.4.0
plotly==5.3.1
prometheus-client==0.12.0
prompt-toolkit==3.0.22
protobuf==3.19.1
ptyprocess==0.7.0
pyasn1==0.4.8
pyasn1-modules==0.2.8
pycparser==2.21
Pygments==2.10.0
pyparsing==3.0.6
pyrsistent==0.18.0
python-dateutil==2.8.2
pytz==2021.3
PyYAML==6.0
pyzmq==22.3.0
requests==2.26.0
requests-oauthlib==1.3.0
rsa==4.7.2
scipy==1.4.1
seaborn==0.11.2
Send2Trash==1.8.0
setuptools-scm==6.3.2
six==1.16.0
sniffio==1.2.0
tenacity==8.0.1

# failed here for py38 and py39
tensorboard==2.1.1

tensorflow==2.1.0; python_version <= '3.7'
tensorflow==2.2; python_version == '3.8'
tensorflow==2.5; python_version > '3.8'

tensorflow-estimator==2.1.0
termcolor==1.1.0
terminado==0.12.1
testpath==0.5.0
tomli==1.2.2
tornado==6.1
tqdm==4.62.3
traitlets==5.1.1
typing_extensions==4.0.0
urllib3==1.26.7
wcwidth==0.2.5
webencodings==0.5.1
websocket-client==1.2.1
Werkzeug==2.0.2
wrapt==1.13.3
zipp==3.6.0
muzero37 run-test: commands[9] | python -c 'print((80*"~")+"\n"+"End-of-Commands\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
End-of-Commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
muzero38 create: /home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/.tox/muzero38
muzero38 installdeps: -r/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/requirements.txt
ERROR: invocation failed (exit code 1), logfile: /home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/.tox/muzero38/log/muzero38-1.log
================================== log start ===================================
ERROR: Could not find a version that satisfies the requirement tensorflow==2.1.0 (from versions: 2.2.0rc1, 2.2.0rc2, 2.2.0rc3, 2.2.0rc4, 2.2.0, 2.2.1, 2.2.2, 2.2.3, 2.3.0rc0, 2.3.0rc1, 2.3.0rc2, 2.3.0, 2.3.1, 2.3.2, 2.3.3, 2.3.4, 2.4.0rc0, 2.4.0rc1, 2.4.0rc2, 2.4.0rc3, 2.4.0rc4, 2.4.0, 2.4.1, 2.4.2, 2.4.3, 2.4.4, 2.5.0rc0, 2.5.0rc1, 2.5.0rc2, 2.5.0rc3, 2.5.0, 2.5.1, 2.5.2, 2.6.0rc0, 2.6.0rc1, 2.6.0rc2, 2.6.0, 2.6.1, 2.6.2, 2.7.0rc0, 2.7.0rc1, 2.7.0)
ERROR: No matching distribution found for tensorflow==2.1.0

=================================== log end ====================================
ERROR: could not install deps [-r/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/requirements.txt]; v = InvocationError('/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/.tox/muzero38/bin/python -m pip install -r/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/requirements.txt', 1)
muzero39 create: /home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/.tox/muzero39
muzero39 installdeps: -r/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/requirements.txt
ERROR: invocation failed (exit code 1), logfile: /home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/.tox/muzero39/log/muzero39-1.log
================================== log start ===================================
ERROR: Could not find a version that satisfies the requirement tensorflow==2.1.0 (from versions: 2.5.0rc0, 2.5.0rc1, 2.5.0rc2, 2.5.0rc3, 2.5.0, 2.5.1, 2.5.2, 2.6.0rc0, 2.6.0rc1, 2.6.0rc2, 2.6.0, 2.6.1, 2.6.2, 2.7.0rc0, 2.7.0rc1, 2.7.0)
ERROR: No matching distribution found for tensorflow==2.1.0

=================================== log end ====================================
ERROR: could not install deps [-r/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/requirements.txt]; v = InvocationError('/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/.tox/muzero39/bin/python -m pip install -r/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/requirements.txt', 1)
___________________________________ summary ____________________________________
  muzero37: commands succeeded
ERROR:   muzero38: could not install deps [-r/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/requirements.txt]; v = InvocationError('/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/.tox/muzero38/bin/python -m pip install -r/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/requirements.txt', 1)
ERROR:   muzero39: could not install deps [-r/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/requirements.txt]; v = InvocationError('/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/.tox/muzero39/bin/python -m pip install -r/home/cwm/git/bb.FLXSA/quant/ibaio_dev/demo/ml/rl_dev/demo/alpha-mu/muzero/requirements.txt', 1)
