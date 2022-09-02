# devBook

1스테이지 이후 스테이지 이후부터 발생
보스는 모두 6각형이며
일본 볼로 나올대도 기본형외에는 모두 육각형

1) 기본형
 데미지를 입으면 줄어들고 터진다.
모양 변화 없음

2) 데미지 하프
데미지를 반만 받는다.
빨강

2) 탱커
외곽에 게이지 존재하며 게이지를 먼저 줄여야 한다. 방어막 형성

주황
3) 방탄 
한번에 클리어 되지 않으면 줄어들지 않는다. 

노랑
4) 분리
최초 데미지를 입으면 분리되서 2개가 된다.하나는 멈췄다 이동 다른 하나는 먼저 이동

초록
5) 스피드업
화면 전체 볼의 이동 속도를 올린다. 화면에 없으면 다시 원래 속도로 돌아간다.
파랑

6) 


2. 내 아이템
1) 피버타임
각 스테이지의 최고 수치를 기준으로 하여 설정 된다.
최초 3초에서 시작한다 스테이지 제한이 없다.
좋은 총알을 먹으면 아이템이 무료로 발사된다. (미사일, 폭탄, 레이저)

2) 미사일
기존 아이템 

3) 폭탄
4) 레이저
5) 시계

원래꺼..
<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android" xmlns:tools="http://schemas.android.com/tools" package="com.mabubsangjum.muhanball" android:versionCode="1" android:versionName="1.0">
  <application android:label="@string/app_name" android:icon="@drawable/app_icon">
    <!-- The MessagingUnityPlayerActivity is a class that extends
         UnityPlayerActivity to work around a known issue when receiving
         notification data payloads in the background. -->
    <activity android:name="com.google.firebase.MessagingUnityPlayerActivity" android:configChanges="fontScale|keyboard|keyboardHidden|locale|mnc|mcc|navigation|orientation|screenLayout|screenSize|smallestScreenSize|uiMode|touchscreen">
      <intent-filter>
        <action android:name="android.intent.action.MAIN" />
        <category android:name="android.intent.category.LAUNCHER" />
      </intent-filter>
      <meta-data android:name="unityplayer.UnityActivity" android:value="true" />
    </activity>
    <service android:name="com.google.firebase.messaging.MessageForwardingService" android:permission="android.permission.BIND_JOB_SERVICE" android:exported="false"></service>
  </application>
</manifest>

새거
<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android" xmlns:tools="http://schemas.android.com/tools" package="com.mabubsangjum.muhanball" android:versionCode="1" android:versionName="1.0">
  <application android:label="@string/app_name" android:icon="@drawable/app_icon">
    <!-- The MessagingUnityPlayerActivity is a class that extends
         UnityPlayerActivity to work around a known issue when receiving
         notification data payloads in the background. -->
    <activity android:name="com.google.firebase.MessagingUnityPlayerActivity" android:configChanges="fontScale|keyboard|keyboardHidden|locale|mnc|mcc|navigation|orientation|screenLayout|screenSize|smallestScreenSize|uiMode|touchscreen">
      <intent-filter>
        <action android:name="android.intent.action.MAIN" />
        <category android:name="android.intent.category.LAUNCHER" />
      </intent-filter>
      <meta-data android:name="unityplayer.UnityActivity" android:value="true" />
    </activity>
    <service android:name="com.google.firebase.messaging.MessageForwardingService" android:permission="android.permission.BIND_JOB_SERVICE" android:exported="false"></service>
  </application>
</manifest>















