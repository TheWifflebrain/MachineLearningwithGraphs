# MachineLearningwithGraphs  

This is a school project titled:   
Deep Learning vs Traditional Community Detection on Twitch Accounts  

We downloaded two datasets from online:   
https://snap.stanford.edu/data/twitch_gamers.html (in a folder called twitch_gamers)    
https://snap.stanford.edu/data/twitch-social-networks.html (in a folder called twitch)   

in the twitch folder there are also GraRep embeddings that we made using this Github Repo: https://github.com/benedekrozemberczki/GraRep   
Those are titled xxxxxx_grarep.csv.   
We followed the steps in that readme and got those files.   

The text file named: project_requirements.txt.   
is the packages we used (using anaconda) to run the files using python 3.8.15.   

The folder titled: With_Output   
means that is the files we ran that still has the output that we will use in the paper/presentation.   

GNNS.ipynb  
is a modified file from: https://github.com/Alexander-Belyi/GNNS  
this is ran in google colab. please also make sure you have the right file structure in google drive to access the needed files to run the program.   
the data files that you need are in a folder called gnns_data. Please put this in your google drive in an appropriate place so that the gnns.ipynb can find it.  
In cell 17 it will have  
    network_file_names = [  
        "de.net",  
        "engb.net",  
        "es.net",  
        "fr.net",  
        "ptbr.net",  
        "ru.net",  
        "large.net"  
    ]  
    return network_file_names  
      
First, mount your drive to google colab.   
Second, run the cell that imports his github (2nd cell)    
Third, put the xxxx.net files from the community_algorithm folder in google drive. You will see a folder titled GNNS in your mounted google drive. Open that and go to the networks folder and put the xxxx.net files in there.    

the community_algorithm folder is the folder that we ran again to make sure everything works.     
it contains the same files as the With_Output folder except we just reran them to make sure it is in working order.     
the gnnsdata.ipynb file creates the xxxx.net files needed for the gnns.ipynb.   
please put those files where the gnns.ipynb can see them.    
it also contains xxxx.gexf files to visualize the graphs on the program Gephi.    
