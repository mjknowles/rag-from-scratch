# rag-from-scratch
Based on https://docs.llamaindex.ai/en/stable/examples/low_level/oss_ingestion_retrieval.html

## Get Started
First time:
```bash
# source: https://github.com/oobabooga/text-generation-webui/issues/1534
# Update Ubuntu packages
sudo apt update
sudo apt upgrade

conda install wget
conda create -n rag-from-scratch
conda activate rag-from-scratch

# Add PPA for gcc-11, update packages, install gcc-11, g++-11, update pip and setuptools, install build-essential
sudo add-apt-repository ppa:ubuntu-toolchain-r/test
sudo apt update
sudo apt install gcc-11 g++-11
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-11 60 --slave /usr/bin/g++ g++ /usr/bin/g++-11
pip install --upgrade setuptools wheel
sudo apt-get install build-essential

conda install jupyter          
jupyter notebook                
```

then:

```bash
conda activate rag-from-scratch
jupyter notebook
```
