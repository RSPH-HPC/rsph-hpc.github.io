## Welcome to the RSPH High Performance Computing Page!

Here you may find quick information about how to get started using the RSPH High Performance Computing Cluster.  The cluster is an aggregation of many compute servers used to run large numbers scientfic computations and is available to Faculty, Researchers, Staff and students of RSPH.  

### How to Get an HPC Cluster Account

Faculy, researchers and students of RSPH can gain access to the HPC Compute Cluster through sponsorship of an RSPH faculty member.  (Current RSPH faculty members can self-sponsor their own accounts, of course.)   To request an account, **the sponsoring faculty member or project principal investigator** should submit an IS Help Desk ticket to help@sph.emory.edu with the following information: 

* Full (first and last) name
* Emory NetID of the new account holder
* Current Emory email address
* Name of department and/or Project
* List of any project resources (e.g., user groups) needed

Students requesting access should ask the project PI to send an email requesting to authorize their access. If the access is for part of their graduate studies and not a sponsored project, then the advisor or instructor must send the email requesting access.

### How to Get Help with HPC Cluster Issues

To get assistance with issues involving the use of the HPC cluster, please open a ticket with the SPH help desk and CC: the HPC Manager (keven "dot" haynes "at" emory "dot" edu), to ensure a timely response.  Also it is a good idea to mention "HPC Cluster" in the subject or body of the request to reduce confusion about what is being requested. 




```markdown
~>qhost
HOSTNAME                ARCH         NCPU NSOC NCOR NTHR NLOAD  MEMTOT  MEMUSE  SWAPTO  SWAPUS
----------------------------------------------------------------------------------------------
global                  -               -    -    -    -     -       -       -       -       -
alpha                   lx-amd64       72    2   36   72  0.20  220.3G   18.6G    4.0G    2.3G
alz1                    lx-amd64       56    2   28   56  0.45  251.8G   66.2G  128.0G  467.9M
apple                   lx-amd64       40    2   20   40  1.51  251.9G  162.2G  128.0G  484.6M
banana                  lx-amd64       40    2   20   40  0.85  251.9G   56.9G  128.0G  261.0M
bravo                   lx-amd64       24    2   12   24  0.28   62.9G    3.5G 1024.0M 1024.0M
cbis1                   lx-amd64       40    2   20   40  0.00  125.7G    3.5G    4.0G    1.8G
cbis2                   lx-amd64       40    2   20   40  0.02  125.7G    3.8G    4.0G    1.7G
charlie                 lx-amd64       24    2   12   24  0.25   47.2G    3.8G   13.6G  240.6M
cherry                  lx-amd64       32    2   16   32  1.53  125.9G  125.5G  128.0G   24.0G
condor                  lx-amd64       40    2   20   40  7.00  125.8G  124.2G   96.0G    4.5G
```


### Starter Code

To quickly get started with running jobs on the cluster, you may want to clone our repository of [basic job submission scripts](https://github.com/RSPH-HPC/GridEngine-Scripts).

### Support or Contact

Having trouble with the cluster?  Send a help request to help@sph.emory.edu. 
