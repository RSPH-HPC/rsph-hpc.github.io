## Welcome to the RSPH High Performance Computing Page!

Here you may find quick information about how to get started using the RSPH High Performance Computing Cluster.  The cluster is an aggregation of many compute servers used to run large numbers scientfic computations and is available to Faculty, Researchers, Staff and students of RSPH.  

### How to Get an HPC Cluster Account

Faculy, researchers and students of RSPH can gain access to the HPC Compute Cluster through sponsorship of an RSPH faculty member.  (Current RSPH faculty members can self-sponsor their own accounts, of course.)   To request an account, **the sponsoring faculty member or project principal investigator** should submit an IS Help Desk ticket to help@sph.emory.edu with the following information: 

* Full (first and last) name of new account holder
* Emory NetID of the new account holder
* Current Emory email address
* Name of department and/or Project

Students requesting access should ask the project PI to send an email requesting to authorize their access. If the access is for part of their graduate studies and not a sponsored project, then the advisor or instructor must send the email requesting access.

### How to Get Help with HPC Cluster Issues

To get assistance with issues involving the use of the HPC cluster, please open a ticket with the SPH help desk and CC: the HPC Manager (keven "dot" haynes "at" emory "dot" edu), to ensure a timely response.  Also it is a good idea to mention "HPC Cluster" in the subject or body of the request to reduce confusion about what is being requested. 




```markdown
$ sinfo -a
PARTITION       AVAIL  TIMELIMIT  NODES  STATE NODELIST 
day-long-cpu       up 1-00:00:00     20    mix node[3-14,16-23] 
day-long-cpu       up 1-00:00:00      1  alloc node15 
short-cpu*         up      30:00     22    mix node[1-14,16-23] 
short-cpu*         up      30:00      1  alloc node15 
interactive-cpu    up 2-00:00:00      3    mix node[21-23] 
interactive-cpu    up 2-00:00:00      1   idle node24 
largemem           up 7-01:00:00      1    mix node25 
lau                up   infinite      2   idle node[26-27] 
guo-neurostat      up   infinite      2   idle node[28-29] 
sunlab             up   infinite      2    mix condor,node30 
sunlab             up   infinite      5   idle node[31-35] 
guo-cbis           up   infinite      2   idle cbis[1-2] 
guo-mh             up   infinite      2   idle mh[1-2] 
alz                up   infinite      1    mix alz1 
dynareg            up   infinite      1   idle dynareg1 
gene               up   infinite      9   idle gene[2-10]
...
```

### Getting Started Guide

To quickly get started with running jobs on the cluster, you may want to read our [Getting Started Guide.](https://github.com/RSPH-HPC/Documentation/raw/master/HPC%20Getting%20Started%20Guide.pdf).


### Support or Contact

Having trouble with the cluster?  Send a help request to help@sph.emory.edu. 
