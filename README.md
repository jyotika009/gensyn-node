# ✅ Step-by-Step Setup (Correct Repo)
**1. Clean Up & Re-clone the Right Repo (Before run this command must be save your .pam file )**
---
Copy code
```bash
cd ~
rm -rf rl-swarm
git clone https://github.com/gensyn-ai/rl-swarm.git
cd rl-swarm
```
**2. Create & Activate Virtual Environment**
---
```bash
python3 -m venv .venv
source .venv/bin/activate
```
**3. Install the Correct Requirements
Pick one:**
---

**For CPU only**:

```bash
pip install -r requirements-cpu.txt
```
**if you’re reusing an old .pem file:**
---
**Copy it to ~/rl-swarm/swarm.pem**
**Set correct permission:**
```bash
cp ~/your_backup/swarm.pem ~/rl-swarm/swarm.pem
chmod 600 swarm.pem
```
**Then launch:**
---
```bash
./run_rl_swarm.sh
```
