Headers and librarys used in android apps


cURL:
    build using https://github.com/gcesarmza/curl-android-ios.git
    curl        v7.43.0
    openssl     1.0.1o

boost:
    built using https://github.com/sorccu/Boost-for-Android.git
    boost       1.49.0

    patches:
        disabled --layout=versioned
        added jam setup for 1_49_0 based off of 1_55_0
        updated gcc references from 4.6 to 4.9