# DISTIBUTED-COMPUTING-FINAL-PROJECT
The student section can be executed by the following commands, if we see the main folder, we will be having two sub folders, “blockchain” and “blockchain client”. From the blockchain client path, by running the below command we can the view the student section page

	Python blockchain_client.py -p 8000(here 8000 is the port number, we can run many student sections by changing the port number but have to make sure the reviewer section is not running on the same port as student)

The reviewer section can be executed by the following commands, we have to keep in mind that port 5000 is master port and we have to run this first before running any other nodes on different port, because master node maintains the records of all the nodes that are running in our eco system.
After moving into the blockchain section, we can run the following commands to open the webpage

Master node:
	Python blockchain.py -p 5000
Slave nodes:
	Python blockchain.py -p (5001 to …)
