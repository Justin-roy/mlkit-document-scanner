## 0.0.2

Breaking change: `MlkitDocumentScannerPlugin` now introduces two streams, one of listening to JPEG and one for PDF results. In order to toggle which one of them should receive updates this version adds a new enum, `DocumentScannerResultMode`.

Add `topics` section to the `pubspec.yaml` file.

For more information on its usage, refer to the example and the API documentation.

## 0.0.1

This is the initial release of the plugin. Please beware of the fact that this code is *not* tested, and most likely *not* recommended for production use.
