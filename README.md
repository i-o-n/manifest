ionOS


# Initialize local repository
repo init -u https://github.com/i-o-n/manifest -b pie

# Sync
repo sync -c -jx --force-sync --no-clone-bundle --no-tags

Build
# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch ion_$device-userdebug

# Build the code
$ mka bacon -jX
