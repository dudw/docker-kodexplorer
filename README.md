# docker-kodexplorer

Docker image of [KodExplorer](https://github.com/dudw/docker-kodexplorer)

## Run

`docker run -d -p 80:80 --name kodexplorer -v <path/to/data>:/var/www/html dudw/kodexplorer`

`docker run -d --restart unless-stopped -p 80:80 --name kodexplorer -v /home/kodexplorer:/var/www/html -v /home/data:/var/www/html/data/User/admin/home dudw/kodexplorer`