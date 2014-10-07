Getting Started
---------------

To initialize your local repository using this CuBox-i trees, use this command:

    repo init -u https://bitbucket.com/cuboxi/android.git -b kitkat

Then to sync up:

    repo sync -j[N]

Then to build:

     cd <source-dir>
     source build/envsetup.sh
     lunch cuboxi-user
     make -j[N]

If you need more information or a more detailed guide, click [here to see our forum.](http://www.solid-run.com/community/)

Our official IRC Channels are hosted on Freenode:

[#cubox - USERS](http://webchat.freenode.net/?channels=cubox/)

[#cubox-devel - DEVELOPERS](http://webchat.freenode.net/?channels=cubox-devel/)

