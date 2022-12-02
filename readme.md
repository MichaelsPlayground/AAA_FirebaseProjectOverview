# Firebase Project Overview

28th Nov. 2022

**FirebasePlayground (active)**
* Auth with Email/Password, Google
* Database (Europe)
* Storage
```plaintext
account: Till Schneemann
console: FirebasePlayground
Project ID: fir-playground-1856e
Project number: 1019673864578
Package name: de.androidcrypto.firebaseplayground
```

**FirebaseUploadTutorial (active)**
* Auth with Email/Password, Google, Anonymus
* Database (US)
* Storage
```plaintext
account: Till Schneemann
console: FirebaseTutorial
Project ID: fir-tutorial-73344
Project number: 938397672907
Package name: de.androidcrypto.firebaseuploadtutorial
```

**Android-Chat-App (active)**
* Auth with Email/Password, Google
* Database (Europe)
* Storage
```plaintext
account: Till Schneemann
console: FirebaseChatApp
Project ID: fir-chatapp-a5632
Project number: 912782818694
Package name: com.example.chatapp
```

**ChatAppSdk33 (active)**
**ChatAppSdk33Original (inactive)**
* Auth with Email/Password, Google
* Database (Europe)
* Storage
```plaintext
account: Till Schneemann
console: SimpleChat
Project ID: simplechat-6671c
Project number: 938595332712
Package name: com.example.chatapp
```

**ChatTutorialScaleDrone (inactive)**
*no Firebase console*

**FirebaseChatOwn (inactive)**
*no Firebase console*

**AndroidBubbleChat**
*just for ListView*

**ChatAppExample**
*just for ListView*

**FirebaseStorageUploadFiles (inactive)**
* no Auth
* Database (US) - expired
* Storage - expired
```plaintext
account: Till Schneemann
console: FirebaseStorageUploadFiles
Project ID: fir-storageuploadfiles
Project number: 256052823523
Package name: de.androidcrypto.firebasestorageuploadfiles
```

**Android-Java-Firebase-Login-Example (active ?)**
* Auth with Email/Password
```plaintext
console: FirebaseLogin
Project ID: fir-login-baccf
Project number: 116035850097
Package name: com.bala.firebaselogin
```

**chatAppInAndroidStudio (active ?)**

**chatAppInAndroidStudioEmailAuthWorking (active ?)**
* 
* Auth with Email/Password, Google, Phone
* Database (Europe)
* Storage
```plaintext
account: Till Schneemann
console: AndroidFirebaseChat
Project ID: androidfirebasechat-10c96
Project number: 843468323026
Package name: de.androidcrypto.firebasechat
```

**FirebaseSetupImages**
* screenshots only *

**FirebaseStorageRTDRecyclerview (inactive)**
* no Firebase console*

**FirebaseTutorialLoginEmail (inactive)**
* Auth with Email/Password, Google, Anonymus
* Database (US) - expired
* Storage
```plaintext
account: Till Schneemann
console: FirebaseTutorial
Project ID: fir-tutorial-73344
Project number: 938397672907
Package name: de.androidcrypto.firebaseuploadtutorial
```

**FirebaseUI-Android (active)**
* example from FirebaseUi https://github.com/firebase/FirebaseUI-Android
* Auth with Email/Password, Google, Anonymus
* Database (US) no expire
* Firestore no expire
* Storage
google-services.json shared with FirebaseUiPlayground
```plaintext
account: Till Schneemann
console: FirebaseUiDemo
Project ID: fir-uidemo-5d814
Project number: 1011466351692
Package name: com.firebase.uidemo
```

**FirebaseUIAuthentication (inactive)**
**no Firebase console *
```plaintext
account: Till Schneemann
console: 
Project ID: livecricket-4c4d5
Project number: 
Package name: com.example.chaitanya.firebasemultipledata
```

**FirebaseUserAuthenticationEmail (inactive)**
* Auth with Email/Password
* Firestore Database (US ?) - expired
* Storage # Error in security rules ?
```plaintext
account: Till Schneemann
console: UserAuthEmailPassword
Project ID: userauthemailpassword
Project number: 1074456848583
Package name: de.androidcrypto.firebaseuserauthenticationemail
```
```plaintext
Error fixing:
service-1074456848583@gcp-sa-firebasestorage.iam.gserviceaccount.com as a principle
Cloud Storage for Firebase Service Agent as role
Dienst-Agent für Cloud Storage for Firebase
```


**Sign-In-provider-using-Firebase-in-android-studio (inactive)**
* no Firebase console *
```plaintext
account: Till Schneemann
console: 
Project ID: signinproviders
Project number:
Package name: com.codewithgolap.signinproviders
```

**NotesAppInAndroidStudio (inactive)**
* no Firebase console *

**SimpleChatApp ()**
* Auth with Email/Password
* Database (Europe) - expired
* no Storage
```plaintext
account: Till Schneemann
console: SimpleChatApp
Project ID: simplechatapp-5468c
Project number: 1049455739871
Package name: de.androidcrypto.simplechatapp
```

```plaintext
Error fixing
service-1049455739871@gcp-sa-firebasestorage.iam.gserviceaccount.com as a principle
Cloud Storage for Firebase Service Agent as role
Dienst-Agent für Cloud Storage for Firebase
```

**FirebaseUiPlayground (active)**
* Auth with Email/Password, Google
* Database (US) - expired
* Storage

google-services.json shared with FirebaseUI-Android 
```plaintext
account: Till Schneemann
console: FirebaseUiDemo
Project ID: fir-uidemo-5d814
Project number: 1011466351692
Package name: com.firebase.uidemo
```

**FirestoreRecyclerAdapterDemo (active)**
*Auth with Email/Password
*Firestore Database 
```plaintext
account: Till Schneemann
console: FirestoreRecyclerAdapterDemo
Project ID: chatapplivestream-7fb09
Project number: 253991116436
Package name: com.example.firestorerecycleradapterdemo
```

============================================================================

Projects in fb.samples

**WhatsappChat (active)**
* Auth with Email/Password, Google
* Database (US)
* Storage (US)

```plaintext
account: fb.samples
console: WhatsappChat
Project ID: whatsappchat-df2dc
Project number: 140901286702
Package name: de.androidcrypto.whatsappchat
```

**FirestoreChatApp (active)**
* Auth with Email/Password, Google
* Firestore (Europe)
* Storage (Europe)

```plaintext
account: fb.samples
console: FirestoreChatApp
Project ID: firestorechatapp-12169
Project number: 868425029414
Package name: de.androidcrypto.firestorechatapp
```

**FirebaseCloudMessaging (active)**
* Auth with Email/Password, Google
* Database (Europe)
* Aanalytics (Germany/Deutschland)
```plaintext
account: fb.samples
console: FirebaseCloudMessaging
Project ID: fir-cloudmessaging-b020c
Project number: 1063102112224
Package name: de.androidcrypto.firebasecloudmessaging
```



```plaintext
account: 
console: 
Project ID: 
Project number:
Package name: 
```

Realtime Database rules (**Note: these rules are insecure**):
```plaintext
{
  "rules": {
    ".read": "auth.uid != null",
    ".write": "auth.uid != null"
  }
}
```

Firestore rule (**Note: these rules are insecure**):
```plaintext
rules_version = '2';
service cloud.firestore {
  match /databases/{database}/documents {
    match /{document=**} {
      allow read: if request.auth != null;
   		allow write: if request.auth != null;
    }
  }
}
```

Storage rule (**Note: these rules are insecure**):
```plaintext
rules_version = '2';
service firebase.storage {
  match /b/{bucket}/o {
    match /{allPaths=**} {
      allow read, write: if true;
    }
  }
}
```