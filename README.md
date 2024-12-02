# sflphone-deb-source
sudo dpkg -i --force-all $(ls -1 | grep sflphone | grep -vE "kde|plugin")
