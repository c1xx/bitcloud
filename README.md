# BitCloud Masternode setup & update script

Please note that these scripts are only designed for Ubuntu 16.04. If you use it on another Ubuntu version, errors may occur.
For all scripts, login as **root**!

**For new masternode installation:**

```
sudo bash -c "$(curl -fsSL https://raw.githubusercontent.com/c1xx/bitcloud/master/masternode-setup.sh)"
```
\
**BitCloud bootstrap:**\
Every 3 hours will be our BitCloud bootstrap refreshed. To get latest bootstrap/blockchin files, you need to login as root.
Used path in this bootstrap script is **/root/.bitcloud**

```
sudo bash -c "$(curl -fsSL https://raw.githubusercontent.com/c1xx/bitcloud/master/bootstrap.sh)"
```
\
**For updating an existing masternode:**\
Use this script only if you used my masternode setup script before, otherwise there will be problems.

```
sudo bash -c "$(curl -fsSL https://raw.githubusercontent.com/c1xx/bitcloud/master/masternode-update.sh)"
```
