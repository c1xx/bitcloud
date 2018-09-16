# BitCloud Masternode setup & update script

Please note that these scripts are only designed for Ubuntu 16.04. If you use it on another Ubuntu version, errors may occur.

**For new masternode installation: Login as root, then do:**

```
sudo bash -c "$(curl -fsSL https://raw.githubusercontent.com/c1xx/bitcloud/master/masternode-setup.sh)"
```
\
**BitCloud bootstrap: Login as root, then do:**

Every 3 hours will be our BitCloud bootstrap refreshed. To get latest bootstrap/blockchin files use:

```
sudo bash -c "$(curl -fsSL https://raw.githubusercontent.com/c1xx/bitcloud/master/bootstrap.sh)"
```
\
**For updating an existing masternode: Login as root, then do:**

```
sudo bash -c "$(curl -fsSL https://raw.githubusercontent.com/c1xx/bitcloud/master/masternode-update.sh)"
```
