# qt-5-install-shell-script
How to install Qt5

# install prerequisite
sudo apt-get install vim && \
sudo apt-get install git && \
sudo apt-get install qtcreator && \
sudo apt-get install build-essential libgl1-mesa-dev && \
firefox https://download.qt.io/official_releases/online_installers/ && \

# run qt installer
mkdir ~/qtInstaller && \
cp ~/Downloads/qt-unified-linux-x64-3.0.2-online.run ~/qtInstaller && \
chmod 755 ~/qtInstaller/qt-unified-linux-x64-3.0.2-online.run && \
sudo ~/qtInstaller/qt-unified-linux-x64-3.0.2-online.run
