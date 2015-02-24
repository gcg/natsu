# natsu

Natsu is a simple PHP cli script to make API calls from terminal. 


## usage

download natsu and run it like `php natsu` or if you want, `chmod +x natsu && cp natsu /usr/local/bin/natsu` so you can call it by typing natsu anywhere in your system. 

## notes. 

it will create a .natsu directory in your home at the first run and try to store secret_id secret_key and tokens there. Natsu can re-login if your API calls return 403 http status codes or invalid access token errors. 


## future of natsu 

- profile support for storing multiple tokens for different API endpoints.  