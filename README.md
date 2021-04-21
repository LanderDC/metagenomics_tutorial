<a href="https://rega.kuleuven.be/cev/viralmetagenomics"><img src="https://rega.kuleuven.be/cev/viralmetagenomics/pictures/lovm/image_preview" height="12.5%" width="12.5%" align="right"/></a>

# JM-lab bioinformatics pipeline
[![Generic badge](https://img.shields.io/badge/GitHub-MatthijnssensLab-brightgreen?logo=github)](https://github.com/Matthijnssenslab)
[![Generic badge](https://img.shields.io/badge/NetoVIR-doi.org%2F10.1038%2Fsrep16532-blue)](https://doi.org/10.1038/srep16532)
[![Generic badge](https://img.shields.io/twitter/url?label=%40JMatthijnssens&style=social&url=https%3A%2F%2Ftwitter.com%2FJMatthijnssens)](https://twitter.com/JMatthijnssens)
[![Generic badge](https://img.shields.io/badge/Laboratory%20of%20Viral%20Metagenomics-1877F2?style=flat-square&logo=facebook&logoColor=white)](https://www.facebook.com/MatthijnssensLab)

This repository is intended as a learning tool for new PhD-students, master students, labrotations, interns, etc. The main jupyter notebook gives an overview of the commands needed for the primary analysis of raw NGS data, flavoured with explanations and neat tips & tricks. Basic command-line knowledge is required to be able to complete this tutorial, a Linux introduction course like <a href="https://ryanstutorials.net/linuxtutorial/" target="_blank">this one</a> should suffice.

This tutorial can be followed by running the commands directly from the terminal or within the jupyter notebook. To run a jupyter notebook on the gbiomed teaching server, copy it to the `~/data/jupyternotebooks/` folder and open an internet browser to navigate to [bmw.gbiomed.kuleuven.be](https://bmw.gbiomed.kuleuven.be/) and log in with your KU Leuven credentials. This should finally allow you to run the notebook. You can find more information on how to transfer files to a remote server in the main notebook. Jupyter notebooks can also be provided to the students as html-files.

#### Requirements:

* Internet connection
* KU Leuven credentials
* Basic Linux command-line knowledge
* The Github repository with this jupyter notebook, solutions notebook and files, etc.
* NetoVIR FASTQ-files (named <em>metatoy.&ast;.fastq.gz</em>)
* Bioinformatics mood

#### Disclaimer:
We are working on the teaching server of gbiomed, which is not suited for 'personal use' (i.e. running a lot of samples or using too much cores/threads). Also try to avoid working on the teaching server during exam time (December/January, first two weeks after Easter holiday and June) as the students from the bioinformatics classes otherwise will have problems during their exam.
