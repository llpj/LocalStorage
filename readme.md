Local Storage provides access to your local storage (SD Card) via the Android 4.4 [Storage Access Framework](https://developer.android.com/guide/topics/providers/document-provider.html).

The focus on this app is not on the included UI, but instead on the [LocalDocumentProvider](https://github.com/ianhanniballake/LocalStorage/blob/master/LocalStorage/src/main/java/com/ianhanniballake/localstorage/LocalStorageProvider.java), which provides read and write access to your SD card. In theory, this code can and should be integrated into a file explorer style app to replace the previous GET_CONTENT Intent used in lower API versions.
