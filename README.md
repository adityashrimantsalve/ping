# ping
from docker.io/centos:7
entrypoint ["ping","-c","4"]
cmd ["google.com"]
