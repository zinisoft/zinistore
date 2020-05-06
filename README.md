# zinistore
ZiniStore - Full React Native Service App for Woocommerce

## CHANGE LOG

V1.0.6
> * Add: Setting category and sub category for news
> * Add: Filter for services
> * Fix: UI coupon and coupon detail
> * Fix: UI category title and sub category

### V1.0.4:
> * Fix Ui coupon and coupon detail
> * Fix Ui sub category
> * Fix title category and sub category
> * Add setting category and sub category for news
> * Add filter for services
> * Fix bug and Optimize code

### V1.0.3:
> * Add Paypal payment
> * Add demo setting
> * Fix ads admob
> * Fix list appoinments
> * Fix image sizes
> * Fix bug and Optimize code

### V1.0.2:
> * Add ads firebase
> * Add setting ads firebase from backend
> * Fix title news details
> * Fix UI search
> * Fix bug and Optimize code

### V1.0.1:
> * Add fonts setting
> * Edit color setting
> * Fix bug and Optimize code

### V1.0.0:
> * Release version 1

## COMMANDLINE REFERS
### Export APK debug:
rm -rf android/app/build && react-native bundle --platform android --dev false --entry-file index.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res && cd android && ./gradlew assembleDebug

### Export APK Release:
cd android && ./gradlew assembleRelease

### Check Keystore cert:
keytool -list -keystore my-release.keystore
