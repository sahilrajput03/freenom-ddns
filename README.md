# Readme
Useful for updating ip at freenom domain: https://gist.github.com/a-c-t-i-n-i-u-m/bc4b1ff265b277dbf195

I copied request as curl from the browser and tried to prune them as much I can and tried to update and it seemed almost working but don't know how:

```bash
# encrypting command used:

cookies.txt  from_public_gist  login.sh  README.md  update_record.sh

sops -e -i login.sh
sops -e -i update_record.sh
sops -e -i from_public_gist/ddns-set.sh

# for decryption:
sops -d -i login.sh
sops -d -i update_record.sh
sops -d -i from_public_gist/ddns-set.sh
```
