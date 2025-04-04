<div align="center">

# 💻 Gensyn-ai-Rl-Swarm_Guide {Mac/Linux} 💻

</div>


# Device/System Requirements 🖥️

![image](https://github.com/user-attachments/assets/594d0847-362b-4ea6-9e61-8590105421c8)

❌❌The Node Wont work on low Specs Devices, It can Cause System Crashing if u try on Low Specs Devices

# Pre-Requirements

# Install Python and Other Tools

* For Linux/Wsl

```
sudo apt update && sudo apt install -y python3 python3-venv python3-pip curl wget screen git lsof

```

* For Mac

```
brew install python
```

Check Version

```
python3 --version
```


# Install Node.js , npm & yarn

* For Linux/Wsl

```
  curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash - && sudo apt update && sudo apt install -y nodejs 
```
* Install Yarn (linux)

```
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add - && \
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list && \
sudo apt update && sudo apt install -y yarn

```


* For Mac

```
brew install node && corepack enable && npm install -g yarn
```

* Check version (Linux/Mac)

```
node -v
npm -v
yarn -v
```

<div align="center">

# 💻 Start The Node (Linux/Mac) 

</div>


* 1️⃣ Clone RL-SWARM Repo

```
git clone https://github.com/gensyn-ai/rl-swarm.git
```

* 2️⃣ Navigate to rl-swarm

```
cd rl-swarm
```

* 3️⃣ Create & Activate a Virtual Environment

```
python3 -m venv .venv
source .venv/bin/activate
```

* 4️⃣ Run the swarm Node 🚀

```
./run_rl_swarm.sh
```

- After Running the Avobe command it will promt `Would you like to connect to the Testnet? [Y/n]` Enter `Y`

- A web Pop-Up will appear, It will ask u to Login ( if no web pop-up then u have to paste this on ur brower `http://localhost:3000/`


- Now Login With Your Email Id, Enter OTP and back to ur Terminal/Wsl?

![image](https://github.com/user-attachments/assets/1fed4b08-4ec4-44de-868c-b2d314cd2a02)


- Now U can see A `ORG_ID` On ur Terminal..Save it!



* Now It will promt `Would you like to push models you train in the RL swarm to the Hugging Face Hub? [y/N]` Enter `N`

![image](https://github.com/user-attachments/assets/b63da75d-389a-4ded-9c4e-cd23804d94ef)



![image](https://github.com/user-attachments/assets/35321942-1aa3-47f1-92a3-dae9881b64cd)

Here we go🚀

Its Done ✅

It will Generate Logs Soon🙌









<div align="center">

# FAQ & Troubleshoot 

</div>


# 1️⃣ Solution of OOM errors on MacBook (Memory/Cpu limit)

* Open -
 ```
nano ~/.zshrc
```

* Paste in the file

```
export PYTORCH_MPS_HIGH_WATERMARK_RATIO=0.0
export PYTORCH_ENABLE_MPS_FALLBACK=1
```
* Reload with

```
  source ~/.zshrc
```

# 3️⃣ How to get the Node Name?

* Check the image below to get your Node id!

![image](https://github.com/user-attachments/assets/728c6401-75c8-43b4-973c-e9d515c4b453)



Follow official Docs for more info and Errors!

https://github.com/gensyn-ai/rl-swarm/tree/brian-address-cpu-only-crashes?tab=readme-ov-file#troubleshooting

👉 Join TG for more Updates: https://telegram.me/cryptogg

If U have any issue then open a issue on this repo or Dm me on TG~

Thank U❤️

