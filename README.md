# willnorris/imageproxy with minio s3 cache learning


## How to Running

* create bucket

login http://localhost:9000 
bucket:demo (for cache) myimages for demo
dir: images

* upload images to myimages && set policy to public * readonly


* access

`http://localhost:8080/<size>/myimages/<folder>/<imagename>`