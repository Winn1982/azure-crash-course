
![image](https://github.com/user-attachments/assets/b4af7cec-6215-4627-b6de-ddeb2726b475)


<h1>Creating A Resource Group in Azure and An Azure Virtual Machine</h1>
In this tutorial, we will create our first resource group and an Azure virtual machine. We will then use Remote Desktop to sign into our virtual machine to make sure everything worked properly. <br />
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop


<h2>Operating Systems Used </h2>

- Windows 10 (22H2)
<h2>High-Level Steps</h2>

- Go to resource groups in Azure
- Create a Resource Group
- Go to Virtual Machines in Azure 
- Create a Virtual Machine running Windows 10 (22H2)

<h2>Actions and Observations</h2>


![image](https://github.com/user-attachments/assets/941a51fb-74ae-4337-a7fb-e77c4d8a0d5c)

We have started creating our resource group named "Azure-Resource-Group". We will review and create the resource group next. Make sure you note what Region you are selecting, because it has to be the same region for the virtual machine that you create. When done you can click "Review and Create". 
</p>
<br />

![image](https://github.com/user-attachments/assets/00c7f8c6-894e-4acf-90a1-5d7c04772014)

We see that our "Azure Resource Group has been created and is in the default directory. 
</p>
<br />

![image](https://github.com/user-attachments/assets/5f0c4d18-43a3-427c-a21d-fc9e508ff07f)


We will now create our virtual machine, we start out in the default directory by searching for "Virtual Machines" in the search bar. We will then click "Create" so we can start creating a new virtual machine.

</p>
<br />

![image](https://github.com/user-attachments/assets/b76ca780-c841-489b-91a5-c93a1c9dab31)

When we start creating our virtual machine, we have to make sure it links up to our resource group named "Azure-Resource-Group". Also, make sure that the region you picked is the same as the resource group we created. For the virtual machine name we have picked "Azureuser".

![image](https://github.com/user-attachments/assets/6126989b-038a-48aa-afe9-cd07f46e7871)

The virtual machine image we are going to create is Windows 10 Pro version 22H2 and for the size we are going to pick Standard_E2s_v3 - 2 vcpus, 16 GiB memory which should be enough to run our image of Windows 10 Pro Version. Then you will click disk and network, it should automatically create the network for the virtual machine. We will then click "Review+Create" and we will see if our virtual machine is in the default directory.

![image](https://github.com/user-attachments/assets/f4bf0f8a-7af7-4094-86cc-e144d2d44e54)

We can now see our virtual machine is in the default directory. Next we will use Remote Desktop to login to our virtual machine using the public IP address 20.63.21.250

![image](https://github.com/user-attachments/assets/bdc2c00a-337c-479f-b2a9-0d692394b914)

I put the username in and will click logon and the next photo should be the main screen of our virtual machine. 

![image](https://github.com/user-attachments/assets/9529d0dc-8cf9-430d-b250-e4eb0c5b343d)

I used Remote Desktop and logged into the virtual machine and have taken a picture of the "About" screen to show that we are running Windows 10 Pro Version 22H2
