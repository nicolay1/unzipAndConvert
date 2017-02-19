# unzipAndConvert
Will extract all the files of an archive at the root and will convert them to UTF-8.
Pass the name of the archive as a parameter when you execute it.
```
./open_zip.run yourArchive.zip
```

## WARNINGS
* All files must be at root, this program do NOT handle directory recursivity.
* Do NOT use space, accent or other strange stuff to name your files.
* This package need 'typeset', 'unzip', 'sed', 'file' and 'ivconv' package to work.
