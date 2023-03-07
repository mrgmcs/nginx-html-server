# nginx-html-server
nginx docker file witch does serve your custom html file.
You can serve your own html file with nginx.
for assemble files, type this command: ######cat nginxserver.tar.part* > nginxserver.tar</br>
for add image to your docker:###### sudo docker load < nginxserver.tar</br>
for using this image: ######sudo docker run --rm --name nginxserver -v systempath/index.html:/data  (if doesnt work, type -v systempath/index.html:/usr/share/nginx/html)
