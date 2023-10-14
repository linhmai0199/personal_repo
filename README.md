```bash
sudo apt install python3.10-venv
sudo python3 -m venv python/.venv
source python/.venv/bin/activate
sudo pip install -r python/requirements.txt
dbt deps
```