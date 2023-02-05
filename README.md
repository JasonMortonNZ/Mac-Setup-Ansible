# Instructions

1. Install ansible `python3 -m pip install --user ansible`
2. Add ansible to PATH `export PATH="$HOME/Library/Python/3.9/bin:$PATH"`
3. Install ansible dependencies `ansible-galaxy install -r requirements.yml`
4. Bootstrap `chmod +x bin/bootstrap && ./bin/bootstrap`
5. Run ansible playbook `chmod +x bin/apply && ./bin/apply`

