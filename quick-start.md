# Quick Start

{% hint style="info" %}
**Good to know:** Make sure you have ubuntu 20.04 with python 3.8, use WSL if you're on Windows 10+.&#x20;

If you're familiar with python, choose any system you like.
{% endhint %}

## Get the source code

Open the terminal:

```
sudo apt install git
git clone 
cd 
```

## Install the pre-requisites&#x20;

Make sure you have ubuntu 20.04 with python 3.8, use WSL if you're on Windows 10+.

```
sudo apt update
sudo apt upgrade
sudo apt install python3-pip build-essential libsnappy-dev zlib1g-dev libbz2-dev libgflags-dev liblz4-dev librocksdb-dev
pip3 install -r requirement.txt
```

## Run the node

Make sure you have public IP and PORT.

```
python3 node.py --name [the node name] --host [the IP] --port [the PORT]
```

If you test on your local environment, 127.0.0.1 is fine.
