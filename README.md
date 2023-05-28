
# RedJs

RedJs is a javascript enumration tool that can be used to crawl a website and download all javascript files. Also look for specific keywords and endpoints




## Installation in linux

Download from releases

```bash
  unzip redjs-linux.zip
  cd redjs-linux.zip
  sudo cp redjs /bin
```


## How to use

```bash
# To Crawl A Website And Download All Js Files 
redjs -u https://example.com -o /a/folder/absolute/path

# To Download From A List Of Url
redjs -f /path/to/jsurl.txt

# To Run redjs Automated Test
redjs -t /oath to/folder/where/files/saved
```


