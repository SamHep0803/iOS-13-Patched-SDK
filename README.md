# iOS-13-Patched-SDK
iOS13 Patched SDK for jailbreak development

For use in jailbreak tweak and app development.
## To use
For use with theos (assuming you have set up enviroment variables for theos):

    curl -LO https://github.com/SamHep0803/iOS-13-Patched-SDK/archive/master.zip
    TMP=$(mktemp -d)
    unzip master.zip -d $TMP
    mv $TMP/iOS-13-Patched-SDK-master/*.sdk $THEOS/sdks
    rm -r master.zip $TMP
