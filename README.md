# minecraft-downloader-core
A minecraft downloader written in node.js

# What is this?
It is an automated downloader for minecraft. Currently only works for vanilla mc and release versions. Snapshots, fabric and forge compatibility will follow soon.

# How to use it?
Run node question.js which will ask you to enter the version number(for example 1.19) and type, which will be either "release" or "snapshot" (cave sensitive).
Works only for release now.

The script will log the inputs and then close.
After that run node app.js and wait for installation to be over.

Some parts of the downloader (like assets.js) have been purposely slowed down to prevent process hanging.

# Features
Works on Windows and Linux as well.
Has an inbuilt file checker to check file integrity after download, and redownload corrupted files(automated).