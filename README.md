# Probe-my-Pathway

This is a project I did during my MSc, where I mapped chemical tools (compounds used in biochemical/cellular assays to study protein function) onto human biological pathways. The purpose of this project was to identify areas in human biology that are lacking chemical tool development. Here are links to two first-author papers that I published detailing the project ([paper 1](https://www.sciencedirect.com/science/article/pii/S1359644624002691), [paper 2](https://academic.oup.com/database/article/doi/10.1093/database/baae116/7917298?login=false)). Also, my past colleagues and I developed the [PmP database](https://apps.thesgc.org/pmp/) for open-access to the data.

I initially did this project using the ICM (Molsoft, San Francisco) command line language, creating one large .csv file that had all the mapping information with which our technician, Lihua Lu, created the PmP database ([https://apps.thesgc.org/pmp/](https://apps.thesgc.org/pmp/)).

I thought it would be great practice to 'replicate' some of the queries that are possible on the PmP database using SQL, using the raw data that I used to create the large .csv file. I uploaded all the raw data onto the MySQL server running on localhost and wrote some queries that creates results similar to what is found on the database. Heres's a [link to the notebook](https://github.com/angelahjkwak/Probe-my-Pathway/blob/main/PmP_in_SQL.ipynb) where I showcase some of the queries I've written! 

