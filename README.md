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

```bash
ansible-playbook replace.yml
```
