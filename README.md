# ngix-php7
belajar dokerfile

#run app
1. docker build -t lukmanlab/nginx-php-fpm7 . --no-cache
2. docker run -itd --rm -p 8080:80 -v /home/hadi84/website/:/var/lib/nginx/html lukmanlab/nginx-php-fpm7
