OblivioN Project
================


Getting Started
---------------

To initialize your local repository using the OblivioN trees, use a command like this:

    repo init -u git://github.com/OblivioN-Project/manifest_ob.git -b ob7

Then to sync up:

  
    repo sync -c -f --force-sync --no-clone-bundle --no-tags  

Finally to build:

    source build/./envsetup.sh && lunch ob_device-userdebug && make bacon
    
When an update is released:

    make clobber
    
And go for more adventures:

    repo sync -c -f --force-sync --no-clone-bundle --no-tags

