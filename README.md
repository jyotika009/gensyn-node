cd ~
rm -rf rl-swarm
git clone https://github.com/gensyn-ai/rl-swarm.git
cd rl-swarm

python3 -m venv .venv
source .venv/bin/activate

pip install -r requirements-cpu.txt
