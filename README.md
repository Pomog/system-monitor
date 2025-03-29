## Vagrantfile is used to run virtual Linux machine
```bash
vagrant up
```
### add user admin
```bash
sudo adduser admin && usermod -aG sudo admin
```
### run gui
```bash
vagrant ssh

sudo -i
systemctl start gdm3
systemctl status gdm
```
### switching between TTYs
```
Ctrl+Alt+F1 or Ctrl+Alt+F7
```
### windows
```cmd
choco install make -y
```