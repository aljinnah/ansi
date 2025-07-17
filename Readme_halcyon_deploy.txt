We need ansible shell module to run shell script below.
tar xzvf halcyonar-linux-x86_64-v1.0.4177.0.tar.gz; HALCYON_TOKEN='QFW7v62zTT+OpYf7Nsh+RgEA' bash install.sh

command module does not work, because its not able to access the shell varibale HALCYON_TOKEN.
We may have to pass the token as argument or other method if we wnat to use ansible command module.
