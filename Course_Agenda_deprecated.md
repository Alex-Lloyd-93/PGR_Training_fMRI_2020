# Lecture 1 (General): 

  - Pre-requisities:

    Learn basic Bash Scripting. Please follow tutorials and exercises provided at https://github.com/RHULPsychology/Important_Tutorials/blob/master/Bash/Important_Commands.md. For Mac users use the terminal. For windows users install the full version of cmder as a terminal and do the rest of the tutorial. If you need any help in the installation of cmder, please look at the official installation documentation https://github.com/cmderdev/cmder/blob/master/README.md#installation

  - Familiarization with the cluster architecture
  
    You would familiarize yourself with the cluster architecture image that is shared in https://github.com/RHULPsychology/Important_Tutorials/blob/master/README.md. You whould be able to relate to terms like a login node, a master node and worker nodes. This would be very essential to understand how the parallelization would work.  

  - Git usage on the cluster
  
    You would use the following command to update git on the cluster. 

  ```bash
      source /usr/local/apps/psycapps/config/conda_bash_update
  ```

    You would be able to fork a repository from github or create a new repo in github, clone it on the cluster, make changes, git add, git commit and git pull and git push from the command line. It is very important for any further steps. Please refer to the tutorials mentioned in https://github.com/RHULPsychology/Important_Tutorials/blob/master/Git/Important_Links.md
  

  - Learn the basics of how to parallelize processing on the cluster

    This is the practical section that will be covered in the meeting. We will do procedures similar to https://github.com/RHULPsychology/SPM_Cluster_Template as practical exercise. Please have a look at github repository the work beforehand and possibly try to make sense out of it.


# Lecture 2 (MRI specific):

  - How to convert raw DICOM data coming out of the scanner into usable and sharable BIDS format

  - Pre-requisities:

    * What is DICOM?
  
      https://en.wikipedia.org/wiki/DICOM
  
    * What is BIDS and why is it important?
  
      https://bids.neuroimaging.io/
  
      https://sarenseeley.github.io/BIDS-fmriprep-MRIQC.html#why_bids
  
    * What is HeuDiConv?

      https://heudiconv.readthedocs.io/en/latest/
  
  - Heudiconv on cluster
  
    This section will be done as a practical during the meeting. It would help if you could familiarize yourself with the heudiconv scripts that we will use on the cluster. It is available at https://github.com/RHULPsychology/HeudiConv_BIDS_conversion
  
  
  

# Lecture 3 (MRI specific):

  - How to process fMRI data

  - Pre-requisities:

    * Install linux subsystem on windows 10.
  
      Please follow the instructions mentioned in https://github.com/RHULPsychology/Important_Tutorials/blob/master/Windows_Prep_for_Cluster/Linux_Subsystem_Activation.md on your windows system
    
    * Install FSL on linux subsystem
  
      Please follow the instructions mentioned in https://github.com/RHULPsychology/Important_Tutorials/blob/master/fslinstallation_on_windows/instructions.md on your windows system
 
    * Install FSL on Mac
  
      Please follow the instructions mentioned in https://github.com/RHULPsychology/Important_Tutorials/blob/master/fslinstallation_on_windows/instructions.md on your windows system
 
 - Preprocessing and statistical processing of fMRI:

This section will be done as a practical during the meeting. It would help if you could familiarize yourself with fMRI Keywords available at ...

 
 # Lecture 4 (MRI specific):
 
 - Parallel processing of fMRI on the cluster
 
   This section will be done as a practical during the meeting. It would help if you could familiarize yourself with the fsl scripts that we will use on the cluster. It is available at https://github.com/RHULPsychology/HeudiConv_BIDS_conversion
