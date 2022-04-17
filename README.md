# SLURM-cluster-in-docker-on-Raspberry-Pi-4

SLURM cluster in docker on Raspberry Pi 4

To run SLURM cluster in docker on Raspberry Pi 4 execute:

     $ docker-compose -f docker-compose-jupyter.yml up -d

To stop:

     $ docker-compose -f docker-compose-jupyter.yml stop

To check logs:

     $ docker-compose -f docker-compose-jupyter.yml logs -f

     (stop logs with CTRL+c")

To check running containers:

     $ docker-compose -f docker-compose-jupyter.yml ps

To access JupyterLab go to: http://localhost:8888


Based on: https://github.com/rancavil/slurm-cluster
