OblivioN Project
================


Getting Started
---------------

To get started with Android/LineageOS, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the LineageOS trees, use a command like this:

    repo init -u git://github.com/OblivioN-Project/manifest_ob.git -b cm-14.1

Then to sync up:

    

Finally to build:

    source build/./envsetup.sh && lunch ob_device-userdebug && make bacon
    
When an update is released:

    make clobber
    
And go for more adventures:

    repo sync -c -f --force-sync --no-clone-bundle --no-tags

