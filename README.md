locale-generator
================
When building a multi-language website/application, we spend lots of time maintaining consistency of multiple locale files. In our experience, the number of key-value pairs in different locale files may be inconsistent easily.

One of the best way to resolve this problem is to manage these key-value pairs in just one file like Google Spreadsheet and conveter it to each locale file by Locale-generator. In doing so, everyone can edit the Google Spreadsheet simultaneously, and generate locale files without conflict.

![Google spreadsheet to locale files image](http://cwtuan.github.io/locale-generator/google-doc-2-locales.jpg "Google spreadsheet to locale files")

## Usage 
1. Download [LocaleGenerator.zip](http://cwtuan.github.io/locale-generator/LocaleGenerator.zip).
* Open the <a href="http://goo.gl/9498aW" target="_blank">Google Spreadsheet sample</a> 
* Follow the steps:

## Config.txt
* **inputFile**: The path of input file (i.e., locale-sample.xlsx)
* **outputDirectory**: The path of output directory for locale files 
* **removeInputFileOnComplete**: If *true*, remove input file when program end.
* **unicode**: If *true*, generate output locale files in Unicode format. Java application usually use Unicode format. Web application doesn't.

## Further Reading
For web developer, you can use <a href="https://github.com/cwtuan/Locale.js" target="_blank">Locale.js</a> to localizate (i18n) your web app by using the output of Locale-generator.


## License
Apache License Version 2.0.



