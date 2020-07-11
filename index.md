---
layout: lesson
root: .  # Is the only page that doesn't follow the pattern /:path/index.html
permalink: index.html  # Is the only page that doesn't follow the pattern /:path/index.html
---

## HPC OnDemand Web Portal

HPC OnDemand provides an integrated, single access point for HPC
resources on the ManeFrame II (M2) supercomputer.

### Accessing the Portal

Access to the HPC OnDemand web portal requires an existing M2 account.

1.  Go to [hpc.smu.edu](https://hpc.smu.edu/).
2.  Sign in using your SMU ID and SMU password

### JupyterLab

1.  Select "JupyterLab" from the "Interactive Apps" drop-down menu.
2.  Select options required for your JupyterLab instance. These options are the
    same as those requested via a standard Slurm script on M2. For today's
    workshop, leave "Additional environment modules to load", "Custom module
    paths", and "Custom environment settings" blank, set "Partition" to "htc", set
    "Number of hours" to 8, "Number of nodes" to 1, "Cores per node" to 1, "GPUs
    per node" to 0, and "Memory" to 4.
3.  Select "Launch"
4.  Wait for the job to start on M2. When the job starts a new button
    "Connect to JupyterLab" button will appear.
5.  Select "Connect to JupyterLab"
6.  The Jupyter Notebook graphical interface will be presented and
    running on the M2 resource requested.
7.  When finished using the JupyterLab instance, return to the "My
    Interactive Sessions" tab in your browser and select "Delete" and
    "Confirm", when prompted, to cancel the job on M2.

{% include links.md %}
