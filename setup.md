# fdroid
My F-Droid repo

```
pip install git+https://gitlab.com/fdroid/fdroidserver.git

sudo apt update && sudo apt install android-sdk
```



<!-- - name: Install F-Droid server software
    run: |
        sudo add-apt-repository ppa:fdroid/fdroidserver
        sudo apt-get update
        sudo apt-get install fdroidserver -->



```
# Save the output as `CONFIG_YML` repo secret
base64 config.yml
# Save the output as `KEYSTORE_P12` repo secret
base64 keystore.p12
```

sudo apt install git-restore-mtime 
git restore-mtime


cd fdroid
fdroid update --create-metadata
# Or in short
fdroid update -c


sources: https://github.com/xarantolus/fdroid/blob/main/setup.md