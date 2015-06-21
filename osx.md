# OSX

### Uninstall MySQL from OSX

```bash
sudo rm /usr/local/mysql
sudo rm -rf /usr/local/mysql*
sudo rm -rf /Library/StartupItems/MySQLCOM
sudo rm -rf /Library/PreferencePanes/MySQL*
vim /etc/hostconfig # and remove the line MYSQLCOM=-YES-
rm -rf ~/Library/PreferencePanes/MySQL*
sudo rm -rf /Library/Receipts/mysql*
sudo rm -rf /Library/Receipts/MySQL*
sudo rm -rf /var/db/receipts/com.mysql.*
```

### Copy something to clipboard

```bash
echo 'kier pogi' | pbcopy
```
