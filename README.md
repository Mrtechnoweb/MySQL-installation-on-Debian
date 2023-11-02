# MySQL-installation-on-Debian

Download package file from - https://dev.mysql.com/downloads/file/?id=519998

![image](https://github.com/Mrtechnoweb/MySQL-installation-on-Debian/assets/149655221/edcc0b9b-7591-43d2-b9c5-819ef5852450)

Go to directory where you have downloaded and excute this command - sudo apt install ./mysql-apt-config_xxxx_all.deb

A pop-up window appears asking which MySQL product to install. As the required product is preselected, scroll down to Ok and hit Enter to continue installing.

![image](https://github.com/Mrtechnoweb/MySQL-installation-on-Debian/assets/149655221/11e30a91-7ae3-459f-bf93-ef1e23811191)

Wait for the installation to complete.

![image](https://github.com/Mrtechnoweb/MySQL-installation-on-Debian/assets/149655221/b962bcdf-c4b0-41a9-bb33-3d60a8555f2c)


Then, update the apt cache to add the new repository source: - sudo apt update

Finally, install MySQL Workbench by running: - sudo apt install mysql-workbench-community

Press y when asked to confirm the installation and wait for the process to complete.

h1. Launch MySQL Workbench

Once you have installed the software, launch the database management tool:

mysql-workbench

  sudo systemctl start mysql
  sudo systemctl enable mysql
  sudo systemctl status mysql
