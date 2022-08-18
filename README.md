How to sync:
-------------

    repo init -u https://android.googlesource.com/platform/manifest -b android-13.0.0_r3
    curl -L https://github.com/AOSP-XIII/local_manifests/raw/android-13.0/local_manifest.xml --create-dirs -o .repo/local_manifests/local_manifest.xml
    repo sync
