# android-google-firebase-common

Eclipse library project based on:<br/>
`ANDROID_SDK/extras/google/m2repository/com/google/firebase/firebase-common/9.0.1/firebase-common-9.0.1.aar`

**Notes:**
- **_Tag &lt;provider&gt; attribute authorities has invalid character '$'._**<br/>
compiler error requires you to change `${applicationId}` with your Java app package in `AndroidManifest.xml`.<br/>
See [&lt;provider&gt;](https://developer.android.com/guide/topics/manifest/provider-element.html) tag documentation for more details.


**Requires:**
- `Android 2.3.1 (API 9) SDK Platform`
- [dandar3/android-google-play-services-basement](https://github.com/dandar3/android-google-play-services-basement)
- [dandar3/android-google-play-services-tasks](https://github.com/dandar3/android-google-play-services-tasks)

**References:**
- https://developers.google.com/android/guides/releases#may_2016_-_v90
- https://android-developers.blogspot.com/2016/05/google-play-services-90-updates.html

**SVN checkout:**
- https://github.com/dandar3/android-google-firebase-common/tags/9.0.1
