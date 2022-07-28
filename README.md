# Software Mentions notebook

A Jupyter notebook for processing a CSV using the [Software Mentions](https://github.com/ourresearch/software-mentions) detector.

## To use:

1. Make sure you have `docker` and `docker-compose` installed for your OS
2. Open a terminal window, clone the repo and enter the new directory
```
~$ git clone https://github.com/mpfl/sm-notebook
~$ cd sm-notebook
```
3. Edit `.env` to suit your environment.
4. Edit `docker-compose.yml` to remove references to GPU if you do not have one.
5. Pull the containers. This might take a while.
```
~/sm-notebook$ docker-compose pull
```
6. Run the containers.
```
~/sm-notebook$Z docker-compose up
```
7. Keep an eye our for the Jupyter notebook URL and visit it in your web browser
8. In Jupyter, go to the `work` directory, open the notebook and continue following the instructions within.

## To stop the containers

1. Hit `Ctrl` + `C` in your terminal window.
2. Clean up the containers
```
$~/sm-notebook docker-compose down
````
