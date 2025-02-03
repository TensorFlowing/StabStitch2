conda env create -f environment.yml

pip install torch==1.13.1+cu116 -f https://download.pytorch.org/whl/torch_stable.html
pip install torchaudio==0.13.1+cu116 -f https://download.pytorch.org/whl/torch_stable.html
pip install torchvision==0.14.1+cu116 -f https://download.pytorch.org/whl/torch_stable.html

conda env update --file environment.yml --prune
