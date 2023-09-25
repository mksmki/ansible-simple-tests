# Simple Ansible Tests

A collection of very basic test playbooks for Ansible

### How to use this repository

1. Prepare virtual environment
1. Clone repository
1. Run tests

### Virtual Environment preparation

```bash
# Create Python Virtual Environment
$ python3 -m venv .venv

# Activate venv
$ source .venv/bin/activate

# Upgrade pip
(.venv) $ python -m pip install -U pip

# Install Ansible and Linter (optional)
(.venv) $ pip install ansible-core ansible-lint

# Ensure that Ansible is installed properly and is able to run
(.venv) $ ansible --version
```

### Clone repository

```bash
(.venv) $ git clone https://github.com/mksmki/ansible-simple-tests.git
```

### Run tests

```bash
(.venv) $ ansible-playbook main.ansible.yaml
```
