# Connect-VS-Code-to-Azure

To connect VS-code to Microsoft Azure Virtual Machine instance, you need to do the following steps:

1- Create your Virtual Machine + Enable SSH connexion via port 22<br>
2- Install SHH extension in VS code<br>
3- Add new connecxion (click on + button)<br>
4- Tap "ssh -i "path/to/key_file.pem" azureuser@MV-IP-Address (replace azureuser by the name specified while creating your virtual machine, also don't forget to change "\" by "/" on your path if you are using windows).<br>
5- Start working :)
