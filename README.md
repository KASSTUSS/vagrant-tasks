# Vagrant TASK 2
1. In your repository create a branch Module 2 and upload a file named module2.txt with some text. 
2. Install Vagrant and VirtualBox to your local PC. 
3. Create a Vagrantfile that describes launch of 2 VMs (Ubuntu or Centos boxes). 
4. Configure the network and network names of the VMs according to UNIX standard (use your nickname and OS name) 
5. Using the “Shell” provisioner: 
    - Install git and configure connection to your remote GitHub repository 
    - Clone the Module 2 branch and print the content of module2.txt to the console 
6. Check the availability of the VMs using the ping command (ping must work with DNS names between the VMs) 
7. Upload the results manually to the module2 branch of your GItHub repository 

---
#### Start `vagrant up` command:
![Alt text](<Снимок экрана 2024-03-23 020129.png>)

#### Output `module2.txt` value on VM `ubuntu`:
>![Alt text](<Снимок экрана 2024-03-23 020153.png>)

#### Output `module2.txt` value on VM `centos`:
>![Alt text](<Снимок экрана 2024-03-23 020202.png>)

#### SSH connection to VM `ubuntu` from local PC:
>![Alt text](<Снимок экрана 2024-03-23 020310.png>)

#### Echo request (`ping`) to VM `centos` from VM `ubuntu`
>Command: `ping 192.168.14.11`
>>![Alt text](<Снимок экрана 2024-03-23 020539.png>)

#### Echo request (`ping`) to VM `ubuntu` from VM `centos`
>Command: `ping 192.168.14.10`
>>![Alt text](<Снимок экрана 2024-03-23 020728.png>)

