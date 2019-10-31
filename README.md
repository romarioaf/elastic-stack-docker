# elastic-stack-docker
Structure with elasticsearch, logstash and kibana using docker-compose

Note:
If you are using Linux, maybe you should change the value of vm.max_map_count to 262144 from sysctl params.
To do that need you just to perform the command sudo sysctl -w vm.max_map_count=262144
