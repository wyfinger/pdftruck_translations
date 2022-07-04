# PDF Truck interface translations
This is a collaborative project for translating user interface of the [PDFTruck](https://pdftruck.com).

You can help with editing the translation or creating a translation into a new language!

In PDFTruck, a translation is an INI file with the language name starting with an underscore (like `_en.ini`, `_en.ini`, etc.).
When launched, the program determines the system language and, if there is a corresponding file in the `profiles/` subdirectory, loads it.

You can also rename the INI file of the translation by removing the underscore at the beginning, then this translation can be loaded manually in the program itself:

![image](https://user-images.githubusercontent.com/431985/177163566-e6824be6-8106-499b-b19d-ae187f66831a.png)

Translations can contain not only string values, but also other properties of interface elements, as in conversion profiles (see https://pdftruck.com/en/help/#profiles), this can be used when the translated string is longer than the original and does not fits.

Since internal work on translations is carried out in [tolgee.io](https://tolgee.io), original JSON files are also attached to INI files. You can directly edit them and then convert them to INI using the supplied `json2ini.exe` utility.

Since internal work on translations is carried out in [tolgee.io](https://tolgee.io), original JSON files are also attached to INI files. You can directly edit and convert them to INI using the supplied `json2ini.exe` utility.

We are waiting for your PR!
