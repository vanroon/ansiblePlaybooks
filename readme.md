# Ansible playbook for Gitea and Docker

run with:
```
ansible-playbook -i hosts main.yml
```

Only install docker:
```
ansible-playbook -i hosts --tags "install, docker" --skip-tags "runGitea, baseConfig"
```
