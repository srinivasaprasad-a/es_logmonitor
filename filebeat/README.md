Building custom filebeat docker image
For the reason,
filebeat.yml file permissions needs to be changed inside container, so that file can be accessed by both root and filebeat user
> chmod 640 filebeat.yml

