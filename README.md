# Vagrant TASK 3
1. Automate the process of VM creation and configuration of network addresses and network names, defining the number of VMs with a variable. 
2. The number of VMs needs to be input from keyboard and can take a value between 1 and 253 with input validation 
3. Create a custom vagrant box with preinstalled and configured software. 
4. Add your custom vagrant box to the default boxes directory. 
5. Launch 2 VMs using your custom vagrant box and test for the installed software

---

### Creating custom Vagrant box:
Packing empty configured VM for Vagrant:
![Alt text](<Снимок экрана 2024-04-16 203711.png>)

Preinstall and configure software(`Nginx`)
![Alt text](<Снимок экрана 2024-04-16 205243.png>)

Packing custom configured VM with preinstalled and configured software for Vagrant and add packed vagrant box to vagrant box list:
![Alt text](<Снимок экрана 2024-04-16 205840.png>)

### Run `vagrant up` command:
![Alt text](<Снимок экрана 2024-04-16 213844.png>)


### Test for the installed software:
##### VM1:
![Alt text](<Снимок экрана 2024-04-16 213810.png>)
##### VM2:
![Alt text](<Снимок экрана 2024-04-16 213816.png>)
##### VM3:
![Alt text](<Снимок экрана 2024-04-16 213824.png>)