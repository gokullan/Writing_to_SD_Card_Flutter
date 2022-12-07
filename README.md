# sd_card

A Flutter application that illustrates writing files to SD Card.

## Note

Starting from Android 11, accessing external storage has become more secure. Add the following permission to android/app/src/main/AndroidManifest.xml:
`<uses-permission android:name="android.permission.MANAGE_EXTERNAL_STORAGE"/>`

## Dependencies (external)

- [external_path](https://pub.dev/packages/external_path)
- [permission_handler](https://pub.dev/packages/permission_handler)

## References

- [Storage updates in Android 11](https://developer.android.com/about/versions/11/privacy/storage)
- [Reading and Writing Files](https://docs.flutter.dev/cookbook/persistence/reading-writing-files)

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
