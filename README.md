# Deploy a dev environment for rust

1. Prepare the host
```sh
sudo chmod +x install.sh
./install.sh
```

2. Deploy
```sh
ansible-playbook -i hosts --ask-pass deploy.yml -v
```
