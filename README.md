# Late-Entry-Project-
An offline friendly Barcode Scanner app. It allows users to swiftly mark students as late either by scanning their barcodes or manually entering their student numbers.
# featurres
Barcode scanner Android application, based on MVVM Architecture
An offline friendly app
Handled edge cases related to multiple clicks, multiple toasts, asking user permission, etc.
GitHub Actions & Firebase App distribution for CI/CD to reduce testing time by 20%
Implemented R8 to reduce apk size by 28.5%
# Functionality 💻

The user must authenticate himself first in order to start scanning
The app provides a quick barcode scanner, with an option to enable flash
In case of damaged camera/barcode, the user can manually enter student number and register a late entry
On scanning or manually entering data, student details pops up with name, branch, admission year, image, & student no (which are stored in app's database to provide quicker access)
In offline scenario, all entries are stored in app's database, & can be synced with the server afterwards
The Settings page include the option to sync locally stored student details & late entry records and other options related to the user
