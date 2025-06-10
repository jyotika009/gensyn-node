# ✅ Step-by-Step Setup (Correct Repo)
**1. Clean Up & Re-clone the Right Repo**
---
Copy code
```bash
cd ~
rm -rf rl-swarm
git clone https://github.com/gensyn-ai/rl-swarm.git
cd rl-swarm
```
**2. Create & Activate Virtual Environment**
```bash
python3 -m venv .venv
source .venv/bin/activate
```
**3. Install the Correct Requirements
Pick one:**

### For **CPU only**:

```bash
pip install -r requirements-cpu.txt
```
