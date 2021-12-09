Taxi Trip Data Report

This Project required Docker Environment.

After clone the repository, please run following codes in your command: 

First time only

`docker pull heweiron/my-jupyter`

Then cd to the repo folder and run

`docker run --rm -p 4040:4040 -p 8888:8888 -v $(pwd):/home/jovyan/work heweiron/my-jupyter start-notebook.sh`
