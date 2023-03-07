# conky-sticky-notes
Sticky notes using Conky for legion5 at bottom near logo. To add note edit ~/Documents/conky-notes.txt

```
sudo dnf install conky # Fedora
sudo apt install conky # Debian
cd /tmp
git clone https://github.com/prasanthc41m/conky-sticky-notes.git
cd conky-sticky-notes
sudo mv conky-notes.conf /etc/conky/
sudo mv conky-startup.sh /etc/conky/
mv conky-notes.desktop ~/.config/autostart/
sudo chmod +x /etc/conky/conky-startup.sh
touch ~/Documents/conky-notes.txt
```
