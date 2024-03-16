# MLKit Document Scanner

Flutter plugin bringing [MLKit Document Scanner](https://developers.google.com/ml-kit/vision/doc-scanner)
to Flutter. Currently only available on Android.

**Heavy work in progress.**

## Usage

From the usage point of view, this plugin is very simple. Simply create an instance:

```dart
final mlkitDocumentScannerPlugin = MlkitDocumentScannerPlugin();
```

and call the `startDocumentScanner` method. Refer to API documentation to learn more about its parameters.

Data that comes back is a binary stream of PDF data. You can observe it using the `scanResults` stream.
