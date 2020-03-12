# File Share Client
Serve your shared folder with auto copy-to-clipboard URL

## Usage

* Clone the project
* `cd` and run `npm install -g`
* Configure the default shared directory and port
```
$ localshare config -d /path/to/your/shared/dir -p 8888
```
* Start the service
```
$ localshare start -d /path/to/another/shared/dir
```
* Share the file
```
$ localshare start -d /path/to/your/file
