## android-google-firebase-common

Eclipse library project based on:<br/>
`ANDROID_SDK/extras/google/m2repository/com/google/firebase/firebase-common/11.0.2/firebase-common-11.0.2.aar`

**Notes:**
- **_Tag &lt;provider&gt; attribute authorities has invalid character '$'._**<br/>
compiler error requires you to change `${applicationId}` with your Java app package in `AndroidManifest.xml`.<br/>
See [&lt;provider&gt;](https://developer.android.com/guide/topics/manifest/provider-element.html) tag documentation for more details.


**Requires:**
- `Android 7.1 (API 25) SDK Platform`
- [dandar3/android-google-play-services-basement](https://github.com/dandar3/android-google-play-services-basement/tree/11.0.2)
- [dandar3/android-google-play-services-tasks](https://github.com/dandar3/android-google-play-services-tasks/tree/11.0.2)

**References:**
- https://firebase.google.com/support/release-notes/android#20170629
- https://developers.google.com/android/guides/releases#june_2017_-_version_110

**SVN checkout:**
- _File > Import... > Team > Team Project Set > URL:_<br/>
  https://raw.githubusercontent.com/dandar3/android-google-firebase-common/11.0.2/.projectset
- _File > Import... > SVN > Project from SVN > Create a new repository location > URL:_<br/> 
  https://github.com/dandar3/android-google-firebase-common/tags/11.0.2
