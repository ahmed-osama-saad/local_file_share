## File Sharing Util

This to share files over the network create and place the files you want to share in the ```share/``` folder the run ```docker-compose up -d```

Open your web browser and navigate to http://localhost:8080. You should see the files and directories from your Docker volume listed.

if you want to change the shared folder name edit the ```docker-compose.yml``` file and change the ```share``` path name to whatever you want.