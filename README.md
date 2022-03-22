Installation Guide 

 
1.	Extract folder “QAS_application” to System path, e.g., “C:\”
2.	Download the CORD-19 dataset: https://ai2-semanticscholar-cord-19.s3-us-west-2.amazonaws.com/historical_releases.html

3.	From CORD-19, copy the folders metadata.csv and pdf_json (document_parses > pdf_json) to “C:\ QAS_application”

4.	install the Docker desktop app following the instructions: https://www.docker.com/products/docker-desktop

5.	Start Docker

6.	Change settings:

a.	in Settings > Ressources > FILE SHARING press the „+“ button, to add the path of the applications, e.g., “C:\application”
b.	In Settings > Resources > FILE SHARING allocate sufficient CPUs, memory, and disk image size (100 GB)

7.	Open the command line tool (Windows: type cmd in windows search. Mac: open terminal) and navigate to the main folder of the project: cd <path to folder>/ QAS_application/      e.g., “C:\ QAS_application”

8.	Type docker-compose up within the command line tool. This step initiates and starts the database, and starts the web app. This command may take very long.

9.	A successful system start shows the message:  ### QAS-CORD19 STARTING ### which can be accessed from a browser through the following address: 127.0.0.1:8000

10.	To shutdown the system press CTRL + C

