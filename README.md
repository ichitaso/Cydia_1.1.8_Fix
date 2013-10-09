Cydia 1.1.8+ for iPhone 4 iOS 7 fixed

Use Xcode 5.0 and iPhoneOS6.1.sdk

1. git clone git://git.saurik.com/cydia.git
2. git clone https://github.com/ichitaso/cydia.git
3. install Fink (the only sane choice)
4. activate Fink (. /sw/bin/init.sh)
5. sudo fink install bash ldid tar wget xz
6. ./sysroot.sh
7. make package
