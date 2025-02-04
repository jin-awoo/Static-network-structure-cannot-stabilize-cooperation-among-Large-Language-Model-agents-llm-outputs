# Static Network Structure Cannot Stabilize Cooperation Among Large Language Model Agents

This repository contains the **raw outputs**, including dialogs, choices, and network data from the paper “Static Network Structure Cannot Stabilize Cooperation 
Among Large Language Model Agents”.

---

Folder Descriptions.  
	•	/mix folders: Results from experiments conducted in well-mixed structures, where agents interact without predefined network constraints.  
	•	/network folders: Results from experiments conducted in networked structures, where agents interact based on a static network configuration.  


Files:  
	•	choices.txt: Records the choices made by each LLM (Large Language Model) during the experiments, round by round.  
	•	dialogs.txt: Logs the dialog histories of each LLM, capturing the interactions and exchanges that occurred during the experiments.  
	•	G.pkl: Contains the network structure used for the experiments:  
	   &nbsp;&nbsp;•	In networked experiments, this file represents the static network structure.  
	   &nbsp;&nbsp;•	In well-mixed experiments, it records the network structure of the final round of the game.  