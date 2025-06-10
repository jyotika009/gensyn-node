cd ~
rm -rf rl-swarm
git clone https://github.com/gensyn-ai/rl-swarm.git
cd rl-swarm

python3 -m venv .venv
source .venv/bin/activate

pip install -r requirements-cpu.txt

# 🚀 Gensyn RL-Swarm Node Setup Guide + All Solutions

Easily set up and run your Gensyn RL-Swarm node on **Linux/WSL** or **Mac**.  
**All commands are copy-paste ready!**

---

## 🛠️ Prerequisites

### For **Linux/WSL**:

```bash
sudo apt update && sudo apt install -y python3 python3-venv python3-pip curl wget screen git lsof
```
