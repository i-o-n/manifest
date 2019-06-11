## >ion ##


## Initialize local repository ##
```bash
repo init -u https://github.com/i-o-n/manifest -b pie
```

## Sync ##
```bash
repo sync -c -jx --force-sync --no-clone-bundle --no-tags
```

## Build & Set up environment ##
```bash
$ . build/envsetup.sh
```

## Choose a target ##
```bash
$ lunch ion_$device-userdebug
```

## Build the code ##
```bash
$ mka bacon -jX
```
