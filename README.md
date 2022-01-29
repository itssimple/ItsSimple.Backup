# It's Simple Backups

A web based UI to manage backups, with service workers that connect to the web server, for a centralized backup feeling.

## Features
- Web UI with simple dashboards and widgets to keep track of backup speed, storage size, and so on.
- Worker services to be installed on target machines to be backed up
- Options to use local storage, or something with S3 support (Amazon S3, Minio)

This project exists more or less because at work (@MultinetInteractive), we have some issues with currently existing backup systems
either being too slow, or they're not reliant enough. (Crashes, doesn't retry fails, bad reporting of errors)

So, it will be my own try, to make something that's useful for people, in need of a backup system where you don't
have to sit in lots of configure files, and manually mapping things up for backup.

Everything should be able to be setup directly from the Web UI, except installation of the workers.

But even the workers will have cross platform installation scripts, for an easy installation and usage.