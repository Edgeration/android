Edgeration
===========

Downloading Source Code:
========================

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

```bash
repo init -u https://github.com/Edgeration/android.git -b edgeration-0.2
```

Then to sync up:
================

```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

