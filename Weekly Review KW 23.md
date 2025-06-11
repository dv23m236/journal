# Weekly Review Template

## Tasks and Progress

- **NUT**
- **Documentation**
- **School Learning**


## Weekly Summary

On Monday I was at HPC and documented the work done so far. On Tuesday, I mainly dealt with NUT (Network UPS Tools). I read up on how NUT works and also watched some videos about it. Then I started with the installation. On Wednesday, Mathis gave me the task of installing and deploying both NUT and NUT Monitoring. Both were to be implemented in containers using Docker. However, the attempt to deploy NUT completely in a container was not successful. Therefore I deleted the VM and created a new one on which I installed NUT directly on the VM, while continuing to deploy NUT monitoring using Docker. On Wednesday afternoon I took some time to look at my school stuff.

## Problems and Assistance

- **Problems encountered:**

- As I started NUT and NUT Monitoring, NUT kept crashing because it didn't had any data. I was also unable to access the NUT Monitoring web interface as it was not receiving any data from NUT either.


- **Assistance needed for the problems:**

- I tried to solve the problem myself by customizing the script with dummy data, but that didn't work. Mathis later explained to me that it generally doesn't work to implement everything completely with Docker. So I started all over again.



## Reflection
The documentation of previous work went well. The independent introduction to a new tool and setting up the environment also went well. Troubleshooting was challenging, especially because the cause was not immediately obvious. Looking back, I could have consulted earlier instead of spending too much time with the containerized solution. I learned that not all software is suitable for operation in Docker especially system related services such as NUT. I also realized that you can ask for help earlier instead of trying to solve everything on your own. It's also important to do a clean restart in good time if things get stuck. 


## Outlook for Next Week

- 


## Miscellaneous

- 
