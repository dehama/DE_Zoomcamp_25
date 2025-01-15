# DE_Zoomcamp_25

module 1:
 docker build -t test:pandas .
 docker create based on dockerfile, include a name, do it in . (this) dir
 -t ?

 docker run -it test:pandas
 -it 
 -it is short for --interactive + --tty. When you docker run with this command it takes you straight inside the container.

 -d is short for --detach, which means you just run the container and then detach from it. Essentially, you run container in the background.

Edit: So if you run the Docker container with -itd, it runs both the -it options and detaches you from the container. As a result, your container will still be running in the background even without any default app to run.


 ENTRYPOINT [ "bash"]
what needs to be started: bash command terminal
 ENTRYPOINT [ "python", "pipeline.py"]
 what needs to be started: python command, execute py command

 