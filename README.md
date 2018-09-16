# BitCloud Masternode setup & update script

Please note that these scripts are only designed for Ubuntu 16.04. If you use it on another Ubuntu version, errors may occur.

**For new masternode installation use:**

```
sudo bash -c "$(curl -fsSL https://raw.githubusercontent.com/c1xx/bitcloud/master/masternode-setup.sh)"
```

**BitCloud bootstrap:**

Every 3 hours will be our BitCloud bootstrap refreshed. To get latest bootstrap/blockchin files use:

```
sudo bash -c "$(curl -fsSL https://raw.githubusercontent.com/c1xx/bitcloud/master/bootstrap.sh)"
```

**For updating an existing masternode use:**

```
sudo bash -c "$(curl -fsSL https://raw.githubusercontent.com/c1xx/bitcloud/master/masternode-update.sh)"
```
