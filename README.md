## google-firebase-common

Eclipse library project based on:<br/>
https://maven.google.com/com/google/firebase/firebase-common/19.5.0/firebase-common-19.5.0.aar

**Import:**
- _File > Import... > Team > Team Project Set > URL:_<br/>
  https://raw.githubusercontent.com/dandar3/android-google-firebase-common/19.5.0/.projectset

**Notes:** <img src="https://raw.githubusercontent.com/google/material-design-icons/main/png/alert/error_outline/materialicons/24dp/1x/baseline_error_outline_black_24dp.png" align="top" />
- _Tag **&lt;provider&gt;** attribute **authorities** has invalid character '$'._<br/>
  Replace `${applicationId}` with your own application package in this `AndroidManifest.xml`<br/>
  See [&lt;provider android:authorities&gt;](https://developer.android.com/guide/topics/manifest/provider-element.html#auth) tag documentation for more details.

**Requires:**
- `Android 10 (API 29) SDK Platform`

**References:**
- https://firebase.google.com/support/release-notes/android
- https://developers.google.com/android/guides/releases