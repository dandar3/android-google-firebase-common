## android-google-firebase-common

Eclipse library project based on:<br/>
https://maven.google.com/com/google/firebase/firebase-common/15.0.0/firebase-common-15.0.0.aar

**Notes:**
- **_Tag &lt;provider&gt; attribute authorities has invalid character '$'._**<br/>
compiler error requires you to change `${applicationId}` with your Java app package in `AndroidManifest.xml`.<br/>
See [&lt;provider&gt;](https://developer.android.com/guide/topics/manifest/provider-element.html) tag documentation for more details.


**Requires:**
- `Android 8.1 (API 27) SDK Platform`
- [dandar3/android-google-play-services-basement](https://github.com/dandar3/android-google-play-services-basement/tree/15.0.0)
- [dandar3/android-google-play-services-tasks](https://github.com/dandar3/android-google-play-services-tasks/tree/15.0.0)

**References:**
- https://firebase.google.com/support/release-notes/android#sdk_version_1500_april_12_2018
- https://developers.google.com/android/guides/releases#april_12_2018_-_version_1500

**SVN checkout:**
- _File > Import... > Team > Team Project Set > URL:_<br/>
  https://raw.githubusercontent.com/dandar3/android-google-firebase-common/15.0.0/.projectset
- _File > Import... > SVN > Project from SVN > Create a new repository location > URL:_<br/> 
  https://github.com/dandar3/android-google-firebase-common/tags/15.0.0
