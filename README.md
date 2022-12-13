# Ansible Experiments and POCs

## Installing Ansible and its prerequisites

```bash
sudo apt-get install -y --no-install-recommends \
    python3 \
    python3-dev \
    python3-pip

pip install ansible-core==2.12
```

## Usage

Make sure that Ansible is installed.


Run one of the following commands:

```bash
ansible-playbook replace.yml
ansible-playbook template.yml
```
