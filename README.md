
(base) C:\text-generation-webui>conda activate textgen

(textgen) C:\text-generation-webui>pip3 install torch torchvision torchaudio
Collecting torch
  Downloading torch-2.8.0-cp311-cp311-win_amd64.whl.metadata (30 kB)
Collecting torchvision
  Downloading torchvision-0.23.0-cp311-cp311-win_amd64.whl.metadata (6.1 kB)
Collecting torchaudio
  Downloading torchaudio-2.8.0-cp311-cp311-win_amd64.whl.metadata (7.2 kB)
Requirement already satisfied: filelock in c:\users\shadow\appdata\roaming\python\python311\site-packages (from torch) (3.19.1)
Requirement already satisfied: typing-extensions>=4.10.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from torch) (4.15.0)
Requirement already satisfied: sympy>=1.13.3 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from torch) (1.14.0)
Collecting networkx (from torch)
  Downloading networkx-3.5-py3-none-any.whl.metadata (6.3 kB)
Requirement already satisfied: jinja2 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from torch) (3.1.6)
Requirement already satisfied: fsspec in c:\users\shadow\appdata\roaming\python\python311\site-packages (from torch) (2025.9.0)
Requirement already satisfied: numpy in c:\users\shadow\appdata\roaming\python\python311\site-packages (from torchvision) (2.3.3)
Requirement already satisfied: pillow!=8.3.*,>=5.3.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from torchvision) (10.4.0)
Requirement already satisfied: mpmath<1.4,>=1.1.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from sympy>=1.13.3->torch) (1.3.0)
Requirement already satisfied: MarkupSafe>=2.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from jinja2->torch) (3.0.2)
Downloading torch-2.8.0-cp311-cp311-win_amd64.whl (241.4 MB)
   ---------------------------------------- 241.4/241.4 MB 44.0 MB/s  0:00:05
Downloading torchvision-0.23.0-cp311-cp311-win_amd64.whl (1.6 MB)
   ---------------------------------------- 1.6/1.6 MB 83.7 MB/s  0:00:00
Downloading torchaudio-2.8.0-cp311-cp311-win_amd64.whl (2.5 MB)
   ---------------------------------------- 2.5/2.5 MB 72.4 MB/s  0:00:00
Downloading networkx-3.5-py3-none-any.whl (2.0 MB)
   ---------------------------------------- 2.0/2.0 MB 110.8 MB/s  0:00:00
Installing collected packages: networkx, torch, torchvision, torchaudio
Successfully installed networkx-3.5 torch-2.8.0 torchaudio-2.8.0 torchvision-0.23.0

(textgen) C:\text-generation-webui>pip install -r requirements_cpu_only_noavx2.txt
Ignoring bitsandbytes: markers 'platform_system != "Windows"' don't match your environment
Collecting bitsandbytes==0.41.1 (from -r requirements_cpu_only_noavx2.txt (line 25))
  Downloading https://github.com/jllllll/bitsandbytes-windows-webui/releases/download/wheels/bitsandbytes-0.41.1-py3-none-win_amd64.whl (152.7 MB)
     ---------------------------------------- 152.7/152.7 MB 49.5 MB/s  0:00:03
Ignoring llama-cpp-python: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.11"' don't match your environment
Ignoring llama-cpp-python: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.10"' don't match your environment
Ignoring llama-cpp-python: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.9"' don't match your environment
Ignoring llama-cpp-python: markers 'platform_system == "Linux" and platform_machine == "x86_64" and python_version == "3.8"' don't match your environment
Collecting llama-cpp-python==0.2.23+cpuavx (from -r requirements_cpu_only_noavx2.txt (line 32))
  Downloading https://github.com/jllllll/llama-cpp-python-cuBLAS-wheels/releases/download/cpu/llama_cpp_python-0.2.23+cpuavx-cp311-cp311-win_amd64.whl (1.8 MB)
     ---------------------------------------- 1.8/1.8 MB 102.2 MB/s  0:00:00
Ignoring llama-cpp-python: markers 'platform_system == "Windows" and python_version == "3.10"' don't match your environment
Ignoring llama-cpp-python: markers 'platform_system == "Windows" and python_version == "3.9"' don't match your environment
Ignoring llama-cpp-python: markers 'platform_system == "Windows" and python_version == "3.8"' don't match your environment
Collecting accelerate==0.25.* (from -r requirements_cpu_only_noavx2.txt (line 1))
  Downloading accelerate-0.25.0-py3-none-any.whl.metadata (18 kB)
Requirement already satisfied: colorama in c:\users\shadow\appdata\roaming\python\python311\site-packages (from -r requirements_cpu_only_noavx2.txt (line 2)) (0.4.6)
Collecting datasets (from -r requirements_cpu_only_noavx2.txt (line 3))
  Downloading datasets-4.0.0-py3-none-any.whl.metadata (19 kB)
Collecting einops (from -r requirements_cpu_only_noavx2.txt (line 4))
  Downloading einops-0.8.1-py3-none-any.whl.metadata (13 kB)
Collecting exllamav2==0.0.11 (from -r requirements_cpu_only_noavx2.txt (line 5))
  Downloading exllamav2-0.0.11-py3-none-any.whl.metadata (401 bytes)
Collecting gradio==3.50.* (from -r requirements_cpu_only_noavx2.txt (line 6))
  Downloading gradio-3.50.2-py3-none-any.whl.metadata (17 kB)
Collecting markdown (from -r requirements_cpu_only_noavx2.txt (line 7))
  Downloading markdown-3.9-py3-none-any.whl.metadata (5.1 kB)
Collecting numpy==1.24.* (from -r requirements_cpu_only_noavx2.txt (line 8))
  Downloading numpy-1.24.4-cp311-cp311-win_amd64.whl.metadata (5.6 kB)
Collecting optimum==1.15.* (from -r requirements_cpu_only_noavx2.txt (line 9))
  Downloading optimum-1.15.0-py3-none-any.whl.metadata (17 kB)
Requirement already satisfied: pandas in c:\users\shadow\appdata\roaming\python\python311\site-packages (from -r requirements_cpu_only_noavx2.txt (line 10)) (2.3.2)
Collecting peft==0.7.* (from -r requirements_cpu_only_noavx2.txt (line 11))
  Downloading peft-0.7.1-py3-none-any.whl.metadata (25 kB)
Requirement already satisfied: Pillow>=9.5.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from -r requirements_cpu_only_noavx2.txt (line 12)) (10.4.0)
Requirement already satisfied: pyyaml in c:\users\shadow\appdata\roaming\python\python311\site-packages (from -r requirements_cpu_only_noavx2.txt (line 13)) (6.0.2)
Requirement already satisfied: requests in c:\users\shadow\appdata\roaming\python\python311\site-packages (from -r requirements_cpu_only_noavx2.txt (line 14)) (2.32.5)
Collecting safetensors==0.4.1 (from -r requirements_cpu_only_noavx2.txt (line 15))
  Downloading safetensors-0.4.1-cp311-none-win_amd64.whl.metadata (3.8 kB)
Collecting scipy (from -r requirements_cpu_only_noavx2.txt (line 16))
  Downloading scipy-1.16.2-cp311-cp311-win_amd64.whl.metadata (60 kB)
Collecting sentencepiece (from -r requirements_cpu_only_noavx2.txt (line 17))
  Downloading sentencepiece-0.2.1-cp311-cp311-win_amd64.whl.metadata (10 kB)
Collecting tensorboard (from -r requirements_cpu_only_noavx2.txt (line 18))
  Downloading tensorboard-2.20.0-py3-none-any.whl.metadata (1.8 kB)
Collecting transformers==4.36.* (from -r requirements_cpu_only_noavx2.txt (line 19))
  Downloading transformers-4.36.2-py3-none-any.whl.metadata (126 kB)
Requirement already satisfied: tqdm in c:\users\shadow\appdata\roaming\python\python311\site-packages (from -r requirements_cpu_only_noavx2.txt (line 20)) (4.67.1)
Collecting wandb (from -r requirements_cpu_only_noavx2.txt (line 21))
  Downloading wandb-0.21.4-py3-none-win_amd64.whl.metadata (10 kB)
Requirement already satisfied: typing-extensions>=4.5.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from llama-cpp-python==0.2.23+cpuavx->-r requirements_cpu_only_noavx2.txt (line 32)) (4.15.0)
Collecting diskcache>=5.6.1 (from llama-cpp-python==0.2.23+cpuavx->-r requirements_cpu_only_noavx2.txt (line 32))
  Downloading diskcache-5.6.3-py3-none-any.whl.metadata (20 kB)
Collecting ninja (from exllamav2==0.0.11->-r requirements_cpu_only_noavx2.txt (line 5))
  Downloading ninja-1.13.0-py3-none-win_amd64.whl.metadata (5.1 kB)
Collecting fastparquet (from exllamav2==0.0.11->-r requirements_cpu_only_noavx2.txt (line 5))
  Downloading fastparquet-2024.11.0-cp311-cp311-win_amd64.whl.metadata (4.3 kB)
Requirement already satisfied: torch>=2.0.1 in c:\users\shadow\miniconda3\envs\textgen\lib\site-packages (from exllamav2==0.0.11->-r requirements_cpu_only_noavx2.txt (line 5)) (2.8.0)
Requirement already satisfied: pygments in c:\users\shadow\appdata\roaming\python\python311\site-packages (from exllamav2==0.0.11->-r requirements_cpu_only_noavx2.txt (line 5)) (2.19.2)
Collecting websockets (from exllamav2==0.0.11->-r requirements_cpu_only_noavx2.txt (line 5))
  Downloading websockets-15.0.1-cp311-cp311-win_amd64.whl.metadata (7.0 kB)
Collecting regex (from exllamav2==0.0.11->-r requirements_cpu_only_noavx2.txt (line 5))
  Downloading regex-2025.9.1-cp311-cp311-win_amd64.whl.metadata (41 kB)
Requirement already satisfied: packaging>=20.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from accelerate==0.25.*->-r requirements_cpu_only_noavx2.txt (line 1)) (24.2)
Requirement already satisfied: psutil in c:\users\shadow\appdata\roaming\python\python311\site-packages (from accelerate==0.25.*->-r requirements_cpu_only_noavx2.txt (line 1)) (7.0.0)
Requirement already satisfied: huggingface-hub in c:\users\shadow\appdata\roaming\python\python311\site-packages (from accelerate==0.25.*->-r requirements_cpu_only_noavx2.txt (line 1)) (0.34.4)
Collecting aiofiles<24.0,>=22.0 (from gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6))
  Downloading aiofiles-23.2.1-py3-none-any.whl.metadata (9.7 kB)
Requirement already satisfied: altair<6.0,>=4.2.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (5.5.0)
Requirement already satisfied: fastapi in c:\users\shadow\appdata\roaming\python\python311\site-packages (from gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (0.115.6)
Collecting ffmpy (from gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6))
  Downloading ffmpy-0.6.1-py3-none-any.whl.metadata (2.9 kB)
Collecting gradio-client==0.6.1 (from gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6))
  Downloading gradio_client-0.6.1-py3-none-any.whl.metadata (7.1 kB)
Requirement already satisfied: httpx in c:\users\shadow\appdata\roaming\python\python311\site-packages (from gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (0.28.1)
Collecting importlib-resources<7.0,>=1.3 (from gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6))
  Downloading importlib_resources-6.5.2-py3-none-any.whl.metadata (3.9 kB)
Requirement already satisfied: jinja2<4.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (3.1.6)
Collecting markupsafe~=2.0 (from gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6))
  Downloading MarkupSafe-2.1.5-cp311-cp311-win_amd64.whl.metadata (3.1 kB)
Collecting matplotlib~=3.0 (from gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6))
  Downloading matplotlib-3.10.6-cp311-cp311-win_amd64.whl.metadata (11 kB)
Collecting orjson~=3.0 (from gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6))
  Downloading orjson-3.11.3-cp311-cp311-win_amd64.whl.metadata (43 kB)
Requirement already satisfied: pydantic!=1.8,!=1.8.1,!=2.0.0,!=2.0.1,<3.0.0,>=1.7.4 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (2.11.7)
Collecting pydub (from gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6))
  Downloading pydub-0.25.1-py2.py3-none-any.whl.metadata (1.4 kB)
Requirement already satisfied: python-multipart in c:\users\shadow\appdata\roaming\python\python311\site-packages (from gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (0.0.19)
Collecting semantic-version~=2.0 (from gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6))
  Downloading semantic_version-2.10.0-py2.py3-none-any.whl.metadata (9.7 kB)
Requirement already satisfied: uvicorn>=0.14.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (0.32.1)
Collecting websockets (from exllamav2==0.0.11->-r requirements_cpu_only_noavx2.txt (line 5))
  Downloading websockets-11.0.3-cp311-cp311-win_amd64.whl.metadata (6.8 kB)
Requirement already satisfied: fsspec in c:\users\shadow\appdata\roaming\python\python311\site-packages (from gradio-client==0.6.1->gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (2025.9.0)
Requirement already satisfied: coloredlogs in c:\users\shadow\appdata\roaming\python\python311\site-packages (from optimum==1.15.*->-r requirements_cpu_only_noavx2.txt (line 9)) (15.0.1)
Requirement already satisfied: sympy in c:\users\shadow\appdata\roaming\python\python311\site-packages (from optimum==1.15.*->-r requirements_cpu_only_noavx2.txt (line 9)) (1.14.0)
Requirement already satisfied: python-dateutil>=2.8.2 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from pandas->-r requirements_cpu_only_noavx2.txt (line 10)) (2.9.0.post0)
Requirement already satisfied: pytz>=2020.1 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from pandas->-r requirements_cpu_only_noavx2.txt (line 10)) (2025.2)
Requirement already satisfied: tzdata>=2022.7 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from pandas->-r requirements_cpu_only_noavx2.txt (line 10)) (2025.2)
Requirement already satisfied: charset_normalizer<4,>=2 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from requests->-r requirements_cpu_only_noavx2.txt (line 14)) (3.4.3)
Requirement already satisfied: idna<4,>=2.5 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from requests->-r requirements_cpu_only_noavx2.txt (line 14)) (3.10)
Requirement already satisfied: urllib3<3,>=1.21.1 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from requests->-r requirements_cpu_only_noavx2.txt (line 14)) (2.5.0)
Requirement already satisfied: certifi>=2017.4.17 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from requests->-r requirements_cpu_only_noavx2.txt (line 14)) (2025.8.3)
Requirement already satisfied: filelock in c:\users\shadow\appdata\roaming\python\python311\site-packages (from transformers==4.36.*->-r requirements_cpu_only_noavx2.txt (line 19)) (3.19.1)
Collecting tokenizers<0.19,>=0.14 (from transformers==4.36.*->-r requirements_cpu_only_noavx2.txt (line 19))
  Downloading tokenizers-0.15.2-cp311-none-win_amd64.whl.metadata (6.8 kB)
Requirement already satisfied: jsonschema>=3.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from altair<6.0,>=4.2.0->gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (4.25.1)
Requirement already satisfied: narwhals>=1.14.2 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from altair<6.0,>=4.2.0->gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (2.4.0)
Collecting contourpy>=1.0.1 (from matplotlib~=3.0->gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6))
  Downloading contourpy-1.3.3-cp311-cp311-win_amd64.whl.metadata (5.5 kB)
Collecting cycler>=0.10 (from matplotlib~=3.0->gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6))
  Downloading cycler-0.12.1-py3-none-any.whl.metadata (3.8 kB)
Collecting fonttools>=4.22.0 (from matplotlib~=3.0->gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6))
  Downloading fonttools-4.59.2-cp311-cp311-win_amd64.whl.metadata (111 kB)
Collecting kiwisolver>=1.3.1 (from matplotlib~=3.0->gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6))
  Downloading kiwisolver-1.4.9-cp311-cp311-win_amd64.whl.metadata (6.4 kB)
Requirement already satisfied: pyparsing>=2.3.1 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from matplotlib~=3.0->gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (3.2.3)
Requirement already satisfied: annotated-types>=0.6.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from pydantic!=1.8,!=1.8.1,!=2.0.0,!=2.0.1,<3.0.0,>=1.7.4->gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (0.7.0)
Requirement already satisfied: pydantic-core==2.33.2 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from pydantic!=1.8,!=1.8.1,!=2.0.0,!=2.0.1,<3.0.0,>=1.7.4->gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (2.33.2)
Requirement already satisfied: typing-inspection>=0.4.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from pydantic!=1.8,!=1.8.1,!=2.0.0,!=2.0.1,<3.0.0,>=1.7.4->gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (0.4.1)
Requirement already satisfied: pyarrow>=15.0.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from datasets->-r requirements_cpu_only_noavx2.txt (line 3)) (21.0.0)
Collecting dill<0.3.9,>=0.3.0 (from datasets->-r requirements_cpu_only_noavx2.txt (line 3))
  Downloading dill-0.3.8-py3-none-any.whl.metadata (10 kB)
Collecting xxhash (from datasets->-r requirements_cpu_only_noavx2.txt (line 3))
  Downloading xxhash-3.5.0-cp311-cp311-win_amd64.whl.metadata (13 kB)
Collecting multiprocess<0.70.17 (from datasets->-r requirements_cpu_only_noavx2.txt (line 3))
  Downloading multiprocess-0.70.16-py311-none-any.whl.metadata (7.2 kB)
Collecting fsspec (from gradio-client==0.6.1->gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6))
  Downloading fsspec-2025.3.0-py3-none-any.whl.metadata (11 kB)
Requirement already satisfied: aiohttp!=4.0.0a0,!=4.0.0a1 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from fsspec[http]<=2025.3.0,>=2023.1.0->datasets->-r requirements_cpu_only_noavx2.txt (line 3)) (3.12.15)
INFO: pip is looking at multiple versions of scipy to determine which version is compatible with other requirements. This could take a while.
Collecting scipy (from -r requirements_cpu_only_noavx2.txt (line 16))
  Downloading scipy-1.16.1-cp311-cp311-win_amd64.whl.metadata (60 kB)
  Downloading scipy-1.16.0-cp311-cp311-win_amd64.whl.metadata (60 kB)
  Downloading scipy-1.15.3-cp311-cp311-win_amd64.whl.metadata (60 kB)
Collecting absl-py>=0.4 (from tensorboard->-r requirements_cpu_only_noavx2.txt (line 18))
  Downloading absl_py-2.3.1-py3-none-any.whl.metadata (3.3 kB)
Requirement already satisfied: grpcio>=1.48.2 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from tensorboard->-r requirements_cpu_only_noavx2.txt (line 18)) (1.74.0)
Requirement already satisfied: protobuf!=4.24.0,>=3.19.6 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from tensorboard->-r requirements_cpu_only_noavx2.txt (line 18)) (5.29.5)
Requirement already satisfied: setuptools>=41.0.0 in c:\users\shadow\miniconda3\envs\textgen\lib\site-packages (from tensorboard->-r requirements_cpu_only_noavx2.txt (line 18)) (78.1.1)
Collecting tensorboard-data-server<0.8.0,>=0.7.0 (from tensorboard->-r requirements_cpu_only_noavx2.txt (line 18))
  Downloading tensorboard_data_server-0.7.2-py3-none-any.whl.metadata (1.1 kB)
Collecting werkzeug>=1.0.1 (from tensorboard->-r requirements_cpu_only_noavx2.txt (line 18))
  Downloading werkzeug-3.1.3-py3-none-any.whl.metadata (3.7 kB)
Requirement already satisfied: click>=8.0.1 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from wandb->-r requirements_cpu_only_noavx2.txt (line 21)) (8.2.1)
Requirement already satisfied: gitpython!=3.1.29,>=1.0.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from wandb->-r requirements_cpu_only_noavx2.txt (line 21)) (3.1.45)
Requirement already satisfied: platformdirs in c:\users\shadow\appdata\roaming\python\python311\site-packages (from wandb->-r requirements_cpu_only_noavx2.txt (line 21)) (4.4.0)
Collecting sentry-sdk>=2.0.0 (from wandb->-r requirements_cpu_only_noavx2.txt (line 21))
  Downloading sentry_sdk-2.37.1-py2.py3-none-any.whl.metadata (10 kB)
Requirement already satisfied: aiohappyeyeballs>=2.5.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from aiohttp!=4.0.0a0,!=4.0.0a1->fsspec[http]<=2025.3.0,>=2023.1.0->datasets->-r requirements_cpu_only_noavx2.txt (line 3)) (2.6.1)
Requirement already satisfied: aiosignal>=1.4.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from aiohttp!=4.0.0a0,!=4.0.0a1->fsspec[http]<=2025.3.0,>=2023.1.0->datasets->-r requirements_cpu_only_noavx2.txt (line 3)) (1.4.0)
Requirement already satisfied: attrs>=17.3.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from aiohttp!=4.0.0a0,!=4.0.0a1->fsspec[http]<=2025.3.0,>=2023.1.0->datasets->-r requirements_cpu_only_noavx2.txt (line 3)) (25.3.0)
Requirement already satisfied: frozenlist>=1.1.1 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from aiohttp!=4.0.0a0,!=4.0.0a1->fsspec[http]<=2025.3.0,>=2023.1.0->datasets->-r requirements_cpu_only_noavx2.txt (line 3)) (1.7.0)
Requirement already satisfied: multidict<7.0,>=4.5 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from aiohttp!=4.0.0a0,!=4.0.0a1->fsspec[http]<=2025.3.0,>=2023.1.0->datasets->-r requirements_cpu_only_noavx2.txt (line 3)) (6.6.4)
Requirement already satisfied: propcache>=0.2.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from aiohttp!=4.0.0a0,!=4.0.0a1->fsspec[http]<=2025.3.0,>=2023.1.0->datasets->-r requirements_cpu_only_noavx2.txt (line 3)) (0.3.2)
Requirement already satisfied: yarl<2.0,>=1.17.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from aiohttp!=4.0.0a0,!=4.0.0a1->fsspec[http]<=2025.3.0,>=2023.1.0->datasets->-r requirements_cpu_only_noavx2.txt (line 3)) (1.20.1)
INFO: pip is looking at multiple versions of contourpy to determine which version is compatible with other requirements. This could take a while.
Collecting contourpy>=1.0.1 (from matplotlib~=3.0->gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6))
  Downloading contourpy-1.3.2-cp311-cp311-win_amd64.whl.metadata (5.5 kB)
Requirement already satisfied: gitdb<5,>=4.0.1 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from gitpython!=3.1.29,>=1.0.0->wandb->-r requirements_cpu_only_noavx2.txt (line 21)) (4.0.12)
Requirement already satisfied: smmap<6,>=3.0.1 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from gitdb<5,>=4.0.1->gitpython!=3.1.29,>=1.0.0->wandb->-r requirements_cpu_only_noavx2.txt (line 21)) (5.0.2)
Requirement already satisfied: jsonschema-specifications>=2023.03.6 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from jsonschema>=3.0->altair<6.0,>=4.2.0->gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (2025.9.1)
Requirement already satisfied: referencing>=0.28.4 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from jsonschema>=3.0->altair<6.0,>=4.2.0->gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (0.36.2)
Requirement already satisfied: rpds-py>=0.7.1 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from jsonschema>=3.0->altair<6.0,>=4.2.0->gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (0.27.1)
Requirement already satisfied: six>=1.5 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from python-dateutil>=2.8.2->pandas->-r requirements_cpu_only_noavx2.txt (line 10)) (1.17.0)
Requirement already satisfied: networkx in c:\users\shadow\miniconda3\envs\textgen\lib\site-packages (from torch>=2.0.1->exllamav2==0.0.11->-r requirements_cpu_only_noavx2.txt (line 5)) (3.5)
Requirement already satisfied: mpmath<1.4,>=1.1.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from sympy->optimum==1.15.*->-r requirements_cpu_only_noavx2.txt (line 9)) (1.3.0)
Requirement already satisfied: h11>=0.8 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from uvicorn>=0.14.0->gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (0.16.0)
Requirement already satisfied: humanfriendly>=9.1 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from coloredlogs->optimum==1.15.*->-r requirements_cpu_only_noavx2.txt (line 9)) (10.0)
Requirement already satisfied: pyreadline3 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from humanfriendly>=9.1->coloredlogs->optimum==1.15.*->-r requirements_cpu_only_noavx2.txt (line 9)) (3.5.4)
Requirement already satisfied: starlette<0.42.0,>=0.40.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from fastapi->gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (0.41.3)
Requirement already satisfied: anyio<5,>=3.4.0 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from starlette<0.42.0,>=0.40.0->fastapi->gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (4.10.0)
Requirement already satisfied: sniffio>=1.1 in c:\users\shadow\appdata\roaming\python\python311\site-packages (from anyio<5,>=3.4.0->starlette<0.42.0,>=0.40.0->fastapi->gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (1.3.1)
Collecting cramjam>=2.3 (from fastparquet->exllamav2==0.0.11->-r requirements_cpu_only_noavx2.txt (line 5))
  Downloading cramjam-2.11.0-cp311-cp311-win_amd64.whl.metadata (681 bytes)
Requirement already satisfied: httpcore==1.* in c:\users\shadow\appdata\roaming\python\python311\site-packages (from httpx->gradio==3.50.*->-r requirements_cpu_only_noavx2.txt (line 6)) (1.0.9)
Downloading exllamav2-0.0.11-py3-none-any.whl (102 kB)
Downloading safetensors-0.4.1-cp311-none-win_amd64.whl (277 kB)
Downloading accelerate-0.25.0-py3-none-any.whl (265 kB)
Downloading gradio-3.50.2-py3-none-any.whl (20.3 MB)
   ---------------------------------------- 20.3/20.3 MB 45.7 MB/s  0:00:00
Downloading gradio_client-0.6.1-py3-none-any.whl (299 kB)
Downloading numpy-1.24.4-cp311-cp311-win_amd64.whl (14.8 MB)
   ---------------------------------------- 14.8/14.8 MB 66.5 MB/s  0:00:00
Downloading optimum-1.15.0-py3-none-any.whl (400 kB)
Downloading peft-0.7.1-py3-none-any.whl (168 kB)
Downloading transformers-4.36.2-py3-none-any.whl (8.2 MB)
   ---------------------------------------- 8.2/8.2 MB 73.0 MB/s  0:00:00
Downloading aiofiles-23.2.1-py3-none-any.whl (15 kB)
Downloading importlib_resources-6.5.2-py3-none-any.whl (37 kB)
Downloading MarkupSafe-2.1.5-cp311-cp311-win_amd64.whl (17 kB)
Downloading matplotlib-3.10.6-cp311-cp311-win_amd64.whl (8.1 MB)
   ---------------------------------------- 8.1/8.1 MB 83.5 MB/s  0:00:00
Downloading orjson-3.11.3-cp311-cp311-win_amd64.whl (131 kB)
Downloading semantic_version-2.10.0-py2.py3-none-any.whl (15 kB)
Downloading tokenizers-0.15.2-cp311-none-win_amd64.whl (2.2 MB)
   ---------------------------------------- 2.2/2.2 MB 41.1 MB/s  0:00:00
Downloading websockets-11.0.3-cp311-cp311-win_amd64.whl (124 kB)
Downloading datasets-4.0.0-py3-none-any.whl (494 kB)
Downloading dill-0.3.8-py3-none-any.whl (116 kB)
Downloading fsspec-2025.3.0-py3-none-any.whl (193 kB)
Downloading multiprocess-0.70.16-py311-none-any.whl (143 kB)
Downloading einops-0.8.1-py3-none-any.whl (64 kB)
Downloading markdown-3.9-py3-none-any.whl (107 kB)
Downloading scipy-1.15.3-cp311-cp311-win_amd64.whl (41.2 MB)
   ---------------------------------------- 41.2/41.2 MB 36.4 MB/s  0:00:01
Downloading sentencepiece-0.2.1-cp311-cp311-win_amd64.whl (1.1 MB)
   ---------------------------------------- 1.1/1.1 MB 49.5 MB/s  0:00:00
Downloading tensorboard-2.20.0-py3-none-any.whl (5.5 MB)
   ---------------------------------------- 5.5/5.5 MB 56.0 MB/s  0:00:00
Downloading tensorboard_data_server-0.7.2-py3-none-any.whl (2.4 kB)
Downloading wandb-0.21.4-py3-none-win_amd64.whl (18.7 MB)
   ---------------------------------------- 18.7/18.7 MB 59.2 MB/s  0:00:00
Downloading absl_py-2.3.1-py3-none-any.whl (135 kB)
Downloading contourpy-1.3.2-cp311-cp311-win_amd64.whl (222 kB)
Downloading cycler-0.12.1-py3-none-any.whl (8.3 kB)
Downloading diskcache-5.6.3-py3-none-any.whl (45 kB)
Downloading fonttools-4.59.2-cp311-cp311-win_amd64.whl (2.3 MB)
   ---------------------------------------- 2.3/2.3 MB 64.6 MB/s  0:00:00
Downloading kiwisolver-1.4.9-cp311-cp311-win_amd64.whl (73 kB)
Downloading regex-2025.9.1-cp311-cp311-win_amd64.whl (276 kB)
Downloading sentry_sdk-2.37.1-py2.py3-none-any.whl (368 kB)
Downloading werkzeug-3.1.3-py3-none-any.whl (224 kB)
Downloading fastparquet-2024.11.0-cp311-cp311-win_amd64.whl (671 kB)
   ---------------------------------------- 671.0/671.0 kB 25.6 MB/s  0:00:00
Downloading cramjam-2.11.0-cp311-cp311-win_amd64.whl (1.7 MB)
   ---------------------------------------- 1.7/1.7 MB 90.6 MB/s  0:00:00
Downloading ffmpy-0.6.1-py3-none-any.whl (5.5 kB)
Downloading ninja-1.13.0-py3-none-win_amd64.whl (309 kB)
Downloading pydub-0.25.1-py2.py3-none-any.whl (32 kB)
Downloading xxhash-3.5.0-cp311-cp311-win_amd64.whl (30 kB)
Installing collected packages: pydub, xxhash, websockets, tensorboard-data-server, sentry-sdk, sentencepiece, semantic-version, safetensors, regex, orjson, numpy, ninja, markupsafe, markdown, kiwisolver, importlib-resources, fsspec, fonttools, ffmpy, einops, diskcache, dill, cycler, cramjam, aiofiles, absl-py, werkzeug, scipy, multiprocess, llama-cpp-python, contourpy, wandb, tokenizers, tensorboard, matplotlib, gradio-client, fastparquet, bitsandbytes, transformers, exllamav2, datasets, accelerate, peft, gradio, optimum
  Attempting uninstall: numpy
    Found existing installation: numpy 2.3.3
    Uninstalling numpy-2.3.3:
      Successfully uninstalled numpy-2.3.3
  Attempting uninstall: markupsafe
    Found existing installation: MarkupSafe 3.0.2
    Uninstalling MarkupSafe-3.0.2:
      Successfully uninstalled MarkupSafe-3.0.2
  Attempting uninstall: fsspec
    Found existing installation: fsspec 2025.9.0
    Uninstalling fsspec-2025.9.0:
      Successfully uninstalled fsspec-2025.9.0
  Attempting uninstall: tokenizers
    Found existing installation: tokenizers 0.22.0
    Uninstalling tokenizers-0.22.0:
      Successfully uninstalled tokenizers-0.22.0
ERROR: pip's dependency resolver does not currently take into account all the packages that are installed. This behaviour is the source of the following dependency conflicts.
moviepy 2.1.2 requires numpy>=1.25.0, but you have numpy 1.24.4 which is incompatible.
Successfully installed absl-py-2.3.1 accelerate-0.25.0 aiofiles-23.2.1 bitsandbytes-0.41.1 contourpy-1.3.2 cramjam-2.11.0 cycler-0.12.1 datasets-4.0.0 dill-0.3.8 diskcache-5.6.3 einops-0.8.1 exllamav2-0.0.11 fastparquet-2024.11.0 ffmpy-0.6.1 fonttools-4.59.2 fsspec-2025.3.0 gradio-3.50.2 gradio-client-0.6.1 importlib-resources-6.5.2 kiwisolver-1.4.9 llama-cpp-python-0.2.23+cpuavx markdown-3.9 markupsafe-2.1.5 matplotlib-3.10.6 multiprocess-0.70.16 ninja-1.13.0 numpy-1.24.4 optimum-1.15.0 orjson-3.11.3 peft-0.7.1 pydub-0.25.1 regex-2025.9.1 safetensors-0.4.1 scipy-1.15.3 semantic-version-2.10.0 sentencepiece-0.2.1 sentry-sdk-2.37.1 tensorboard-2.20.0 tensorboard-data-server-0.7.2 tokenizers-0.15.2 transformers-4.36.2 wandb-0.21.4 websockets-11.0.3 werkzeug-3.1.3 xxhash-3.5.0

(textgen) C:\text-generation-webui>python server.py
W0913 16:40:37.975000 6880 site-packages\torch\distributed\elastic\multiprocessing\redirects.py:29] NOTE: Redirects are currently not supported in Windows or MacOs.
C:\Users\Shadow\miniconda3\envs\textgen\Lib\site-packages\transformers\utils\generic.py:441: FutureWarning: `torch.utils._pytree._register_pytree_node` is deprecated. Please use `torch.utils._pytree.register_pytree_node` instead.
  _torch_pytree._register_pytree_node(
C:\Users\Shadow\miniconda3\envs\textgen\Lib\site-packages\transformers\utils\generic.py:309: FutureWarning: `torch.utils._pytree._register_pytree_node` is deprecated. Please use `torch.utils._pytree.register_pytree_node` instead.
  _torch_pytree._register_pytree_node(
C:\Users\Shadow\miniconda3\envs\textgen\Lib\site-packages\transformers\utils\generic.py:309: FutureWarning: `torch.utils._pytree._register_pytree_node` is deprecated. Please use `torch.utils._pytree.register_pytree_node` instead.
  _torch_pytree._register_pytree_node(
2025-09-13 16:40:51 INFO:Loading the extension "gallery"...
Running on local URL:  http://127.0.0.1:7860
ERROR:    Exception in ASGI application
Traceback (most recent call last):
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\uvicorn\protocols\http\h11_impl.py", line 403, in run_asgi
    result = await app(  # type: ignore[func-returns-value]
             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\uvicorn\middleware\proxy_headers.py", line 60, in __call__
    return await self.app(scope, receive, send)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\fastapi\applications.py", line 1054, in __call__
    await super().__call__(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\applications.py", line 113, in __call__
    await self.middleware_stack(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\middleware\errors.py", line 187, in __call__
    raise exc
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\middleware\errors.py", line 165, in __call__
    await self.app(scope, receive, _send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\middleware\cors.py", line 85, in __call__
    await self.app(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\middleware\exceptions.py", line 62, in __call__
    await wrap_app_handling_exceptions(self.app, conn)(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\_exception_handler.py", line 53, in wrapped_app
    raise exc
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\_exception_handler.py", line 42, in wrapped_app
    await app(scope, receive, sender)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 715, in __call__
    await self.middleware_stack(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 735, in app
    await route.handle(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 288, in handle
    await self.app(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 76, in app
    await wrap_app_handling_exceptions(app, request)(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\_exception_handler.py", line 53, in wrapped_app
    raise exc
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\_exception_handler.py", line 42, in wrapped_app
    await app(scope, receive, sender)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 73, in app
    response = await f(request)
               ^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\fastapi\routing.py", line 301, in app
    raw_response = await run_endpoint_function(
                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\fastapi\routing.py", line 214, in run_endpoint_function
    return await run_in_threadpool(dependant.call, **values)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\concurrency.py", line 39, in run_in_threadpool
    return await anyio.to_thread.run_sync(func, *args)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\anyio\to_thread.py", line 56, in run_sync
    return await get_async_backend().run_sync_in_worker_thread(
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\anyio\_backends\_asyncio.py", line 2476, in run_sync_in_worker_thread
    return await future
           ^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\anyio\_backends\_asyncio.py", line 967, in run
    result = context.run(func, *args)
             ^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\miniconda3\envs\textgen\Lib\site-packages\gradio\routes.py", line 335, in main
    return templates.TemplateResponse(
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\templating.py", line 208, in TemplateResponse
    template = self.get_template(name)
               ^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\templating.py", line 131, in get_template
    return self.env.get_template(name)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\jinja2\environment.py", line 1016, in get_template
    return self._load_template(name, globals)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\jinja2\environment.py", line 975, in _load_template
    template = self.loader.load(self, name, self.make_globals(globals))
               ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\jinja2\loaders.py", line 126, in load
    source, filename, uptodate = self.get_source(environment, name)
                                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\jinja2\loaders.py", line 214, in get_source
    with open(filename, encoding=self.encoding) as f:
         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\text-generation-webui\modules\block_requests.py", line 43, in my_open
    file_contents = file_contents.replace(b'\t\t<script\n\t\t\tsrc="https://cdnjs.cloudflare.com/ajax/libs/iframe-resizer/4.3.7/iframeResizer.contentWindow.min.js"\n\t\t\tasync\n\t\t></script>', b'')
                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
TypeError: replace() argument 1 must be str, not bytes
ERROR:    Exception in ASGI application
Traceback (most recent call last):
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\uvicorn\protocols\http\h11_impl.py", line 403, in run_asgi
    result = await app(  # type: ignore[func-returns-value]
             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\uvicorn\middleware\proxy_headers.py", line 60, in __call__
    return await self.app(scope, receive, send)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\fastapi\applications.py", line 1054, in __call__
    await super().__call__(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\applications.py", line 113, in __call__
    await self.middleware_stack(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\middleware\errors.py", line 187, in __call__
    raise exc
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\middleware\errors.py", line 165, in __call__
    await self.app(scope, receive, _send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\middleware\cors.py", line 85, in __call__
    await self.app(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\middleware\exceptions.py", line 62, in __call__
    await wrap_app_handling_exceptions(self.app, conn)(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\_exception_handler.py", line 53, in wrapped_app
    raise exc
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\_exception_handler.py", line 42, in wrapped_app
    await app(scope, receive, sender)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 715, in __call__
    await self.middleware_stack(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 735, in app
    await route.handle(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 288, in handle
    await self.app(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 76, in app
    await wrap_app_handling_exceptions(app, request)(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\_exception_handler.py", line 53, in wrapped_app
    raise exc
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\_exception_handler.py", line 42, in wrapped_app
    await app(scope, receive, sender)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 73, in app
    response = await f(request)
               ^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\fastapi\routing.py", line 301, in app
    raw_response = await run_endpoint_function(
                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\fastapi\routing.py", line 214, in run_endpoint_function
    return await run_in_threadpool(dependant.call, **values)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\concurrency.py", line 39, in run_in_threadpool
    return await anyio.to_thread.run_sync(func, *args)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\anyio\to_thread.py", line 56, in run_sync
    return await get_async_backend().run_sync_in_worker_thread(
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\anyio\_backends\_asyncio.py", line 2476, in run_sync_in_worker_thread
    return await future
           ^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\anyio\_backends\_asyncio.py", line 967, in run
    result = context.run(func, *args)
             ^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\miniconda3\envs\textgen\Lib\site-packages\gradio\routes.py", line 335, in main
    return templates.TemplateResponse(
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\templating.py", line 208, in TemplateResponse
    template = self.get_template(name)
               ^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\templating.py", line 131, in get_template
    return self.env.get_template(name)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\jinja2\environment.py", line 1016, in get_template
    return self._load_template(name, globals)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\jinja2\environment.py", line 975, in _load_template
    template = self.loader.load(self, name, self.make_globals(globals))
               ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\jinja2\loaders.py", line 126, in load
    source, filename, uptodate = self.get_source(environment, name)
                                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\jinja2\loaders.py", line 214, in get_source
    with open(filename, encoding=self.encoding) as f:
         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\text-generation-webui\modules\block_requests.py", line 43, in my_open
    file_contents = file_contents.replace(b'\t\t<script\n\t\t\tsrc="https://cdnjs.cloudflare.com/ajax/libs/iframe-resizer/4.3.7/iframeResizer.contentWindow.min.js"\n\t\t\tasync\n\t\t></script>', b'')
                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
TypeError: replace() argument 1 must be str, not bytes
ERROR:    Exception in ASGI application
Traceback (most recent call last):
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\uvicorn\protocols\http\h11_impl.py", line 403, in run_asgi
    result = await app(  # type: ignore[func-returns-value]
             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\uvicorn\middleware\proxy_headers.py", line 60, in __call__
    return await self.app(scope, receive, send)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\fastapi\applications.py", line 1054, in __call__
    await super().__call__(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\applications.py", line 113, in __call__
    await self.middleware_stack(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\middleware\errors.py", line 187, in __call__
    raise exc
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\middleware\errors.py", line 165, in __call__
    await self.app(scope, receive, _send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\middleware\cors.py", line 85, in __call__
    await self.app(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\middleware\exceptions.py", line 62, in __call__
    await wrap_app_handling_exceptions(self.app, conn)(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\_exception_handler.py", line 53, in wrapped_app
    raise exc
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\_exception_handler.py", line 42, in wrapped_app
    await app(scope, receive, sender)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 715, in __call__
    await self.middleware_stack(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 735, in app
    await route.handle(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 288, in handle
    await self.app(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 76, in app
    await wrap_app_handling_exceptions(app, request)(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\_exception_handler.py", line 53, in wrapped_app
    raise exc
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\_exception_handler.py", line 42, in wrapped_app
    await app(scope, receive, sender)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 73, in app
    response = await f(request)
               ^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\fastapi\routing.py", line 301, in app
    raw_response = await run_endpoint_function(
                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\fastapi\routing.py", line 214, in run_endpoint_function
    return await run_in_threadpool(dependant.call, **values)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\concurrency.py", line 39, in run_in_threadpool
    return await anyio.to_thread.run_sync(func, *args)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\anyio\to_thread.py", line 56, in run_sync
    return await get_async_backend().run_sync_in_worker_thread(
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\anyio\_backends\_asyncio.py", line 2476, in run_sync_in_worker_thread
    return await future
           ^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\anyio\_backends\_asyncio.py", line 967, in run
    result = context.run(func, *args)
             ^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\miniconda3\envs\textgen\Lib\site-packages\gradio\routes.py", line 335, in main
    return templates.TemplateResponse(
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\templating.py", line 208, in TemplateResponse
    template = self.get_template(name)
               ^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\templating.py", line 131, in get_template
    return self.env.get_template(name)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\jinja2\environment.py", line 1016, in get_template
    return self._load_template(name, globals)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\jinja2\environment.py", line 975, in _load_template
    template = self.loader.load(self, name, self.make_globals(globals))
               ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\jinja2\loaders.py", line 126, in load
    source, filename, uptodate = self.get_source(environment, name)
                                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\jinja2\loaders.py", line 214, in get_source
    with open(filename, encoding=self.encoding) as f:
         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\text-generation-webui\modules\block_requests.py", line 43, in my_open
    file_contents = file_contents.replace(b'\t\t<script\n\t\t\tsrc="https://cdnjs.cloudflare.com/ajax/libs/iframe-resizer/4.3.7/iframeResizer.contentWindow.min.js"\n\t\t\tasync\n\t\t></script>', b'')
                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
TypeError: replace() argument 1 must be str, not bytes
ERROR:    Exception in ASGI application
Traceback (most recent call last):
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\uvicorn\protocols\http\h11_impl.py", line 403, in run_asgi
    result = await app(  # type: ignore[func-returns-value]
             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\uvicorn\middleware\proxy_headers.py", line 60, in __call__
    return await self.app(scope, receive, send)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\fastapi\applications.py", line 1054, in __call__
    await super().__call__(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\applications.py", line 113, in __call__
    await self.middleware_stack(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\middleware\errors.py", line 187, in __call__
    raise exc
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\middleware\errors.py", line 165, in __call__
    await self.app(scope, receive, _send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\middleware\cors.py", line 85, in __call__
    await self.app(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\middleware\exceptions.py", line 62, in __call__
    await wrap_app_handling_exceptions(self.app, conn)(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\_exception_handler.py", line 53, in wrapped_app
    raise exc
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\_exception_handler.py", line 42, in wrapped_app
    await app(scope, receive, sender)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 715, in __call__
    await self.middleware_stack(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 735, in app
    await route.handle(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 288, in handle
    await self.app(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 76, in app
    await wrap_app_handling_exceptions(app, request)(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\_exception_handler.py", line 53, in wrapped_app
    raise exc
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\_exception_handler.py", line 42, in wrapped_app
    await app(scope, receive, sender)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 73, in app
    response = await f(request)
               ^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\fastapi\routing.py", line 301, in app
    raw_response = await run_endpoint_function(
                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\fastapi\routing.py", line 214, in run_endpoint_function
    return await run_in_threadpool(dependant.call, **values)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\concurrency.py", line 39, in run_in_threadpool
    return await anyio.to_thread.run_sync(func, *args)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\anyio\to_thread.py", line 56, in run_sync
    return await get_async_backend().run_sync_in_worker_thread(
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\anyio\_backends\_asyncio.py", line 2476, in run_sync_in_worker_thread
    return await future
           ^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\anyio\_backends\_asyncio.py", line 967, in run
    result = context.run(func, *args)
             ^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\miniconda3\envs\textgen\Lib\site-packages\gradio\routes.py", line 335, in main
    return templates.TemplateResponse(
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\templating.py", line 208, in TemplateResponse
    template = self.get_template(name)
               ^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\templating.py", line 131, in get_template
    return self.env.get_template(name)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\jinja2\environment.py", line 1016, in get_template
    return self._load_template(name, globals)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\jinja2\environment.py", line 975, in _load_template
    template = self.loader.load(self, name, self.make_globals(globals))
               ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\jinja2\loaders.py", line 126, in load
    source, filename, uptodate = self.get_source(environment, name)
                                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\jinja2\loaders.py", line 214, in get_source
    with open(filename, encoding=self.encoding) as f:
         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\text-generation-webui\modules\block_requests.py", line 43, in my_open
    file_contents = file_contents.replace(b'\t\t<script\n\t\t\tsrc="https://cdnjs.cloudflare.com/ajax/libs/iframe-resizer/4.3.7/iframeResizer.contentWindow.min.js"\n\t\t\tasync\n\t\t></script>', b'')
                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
TypeError: replace() argument 1 must be str, not bytes
ERROR:    Exception in ASGI application
Traceback (most recent call last):
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\uvicorn\protocols\http\h11_impl.py", line 403, in run_asgi
    result = await app(  # type: ignore[func-returns-value]
             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\uvicorn\middleware\proxy_headers.py", line 60, in __call__
    return await self.app(scope, receive, send)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\fastapi\applications.py", line 1054, in __call__
    await super().__call__(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\applications.py", line 113, in __call__
    await self.middleware_stack(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\middleware\errors.py", line 187, in __call__
    raise exc
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\middleware\errors.py", line 165, in __call__
    await self.app(scope, receive, _send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\middleware\cors.py", line 85, in __call__
    await self.app(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\middleware\exceptions.py", line 62, in __call__
    await wrap_app_handling_exceptions(self.app, conn)(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\_exception_handler.py", line 53, in wrapped_app
    raise exc
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\_exception_handler.py", line 42, in wrapped_app
    await app(scope, receive, sender)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 715, in __call__
    await self.middleware_stack(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 735, in app
    await route.handle(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 288, in handle
    await self.app(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 76, in app
    await wrap_app_handling_exceptions(app, request)(scope, receive, send)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\_exception_handler.py", line 53, in wrapped_app
    raise exc
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\_exception_handler.py", line 42, in wrapped_app
    await app(scope, receive, sender)
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\routing.py", line 73, in app
    response = await f(request)
               ^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\fastapi\routing.py", line 301, in app
    raw_response = await run_endpoint_function(
                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\fastapi\routing.py", line 214, in run_endpoint_function
    return await run_in_threadpool(dependant.call, **values)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\concurrency.py", line 39, in run_in_threadpool
    return await anyio.to_thread.run_sync(func, *args)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\anyio\to_thread.py", line 56, in run_sync
    return await get_async_backend().run_sync_in_worker_thread(
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\anyio\_backends\_asyncio.py", line 2476, in run_sync_in_worker_thread
    return await future
           ^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\anyio\_backends\_asyncio.py", line 967, in run
    result = context.run(func, *args)
             ^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\miniconda3\envs\textgen\Lib\site-packages\gradio\routes.py", line 335, in main
    return templates.TemplateResponse(
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\templating.py", line 208, in TemplateResponse
    template = self.get_template(name)
               ^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\starlette\templating.py", line 131, in get_template
    return self.env.get_template(name)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\jinja2\environment.py", line 1016, in get_template
    return self._load_template(name, globals)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\jinja2\environment.py", line 975, in _load_template
    template = self.loader.load(self, name, self.make_globals(globals))
               ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\jinja2\loaders.py", line 126, in load
    source, filename, uptodate = self.get_source(environment, name)
                                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Shadow\AppData\Roaming\Python\Python311\site-packages\jinja2\loaders.py", line 214, in get_source
    with open(filename, encoding=self.encoding) as f:
         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\text-generation-webui\modules\block_requests.py", line 43, in my_open
    file_contents = file_contents.replace(b'\t\t<script\n\t\t\tsrc="https://cdnjs.cloudflare.com/ajax/libs/iframe-resizer/4.3.7/iframeResizer.contentWindow.min.js"\n\t\t\tasync\n\t\t></script>', b'')
                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
TypeError: replace() argument 1 must be str, not bytes
Traceback (most recent call last):
  File "C:\text-generation-webui\server.py", line 247, in <module>
    create_interface()
  File "C:\text-generation-webui\server.py", line 158, in create_interface
    shared.gradio['interface'].launch(
  File "C:\Users\Shadow\miniconda3\envs\textgen\Lib\site-packages\gradio\blocks.py", line 2115, in launch
    raise ValueError(
ValueError: When localhost is not accessible, a shareable link must be created. Please set share=True or check your proxy settings to allow access to localhost.

(textgen) C:\text-generation-webui>
