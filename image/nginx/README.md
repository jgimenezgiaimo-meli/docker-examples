# Comandos para inicializar el conenedor

* Build Image `docker build -t jgimenezgiai/nginx-html-serve:0.0.1 .`
* Run container `docker run -d -p82:80 --name html-serve jgimenezgiai/nginx-html-serve:0.0.1`
* Stop container `docker stop html-serve`
* Remove container `docker rm html-serve`
 