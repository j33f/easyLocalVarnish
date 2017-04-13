# easyLocalVarnish

## Usage

1. clone this repo
2. edit the docker-compose.yml file to change the host and port
3. do the same with the conf/distant.vcl file
4. launch via typing ```docker-compose up`` into a terminal

## To see the varnish logs

```docker exec -ti varnish varnishlog```
