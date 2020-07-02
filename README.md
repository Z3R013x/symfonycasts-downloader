# SymfonyCasts Downloader
Simple php script to download SymfonyCasts courses.

### Installation
```sh
$ composer install
$ cp src/application.ini src/local.ini // modify download location (if needen)  credentials is not required

modify src/Service/DownloadService.php line 41, authenticate in symfonycast via your browser, get value of phpsessid cookie, cookie value there

i was too lazy to make it read from config file :( 

```

### Usage
```sh
$ php src/console app:download
```
