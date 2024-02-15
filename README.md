[![Showcase](Images/Shared_Memory_1.png?raw=true "Iamge 1")](https://www.youtube.com/watch?v=Ha3e9BBdqis&ab_channel=NordicGamer)

# Shared Memory
Shared memory between Autodesk Maya and custom application. Both programs share a number of files to determine how the structure looks.

# The task of the program
The task of the program itself is to be able to share information between Autodesk Maya and any other real-time program. Mainly, it consists of data from Maya meshes that are stored on a shared memory that other programs can use. Since not only meshes that are being sent, I have divided up different types of data into groups. These parts are: camera, light, material, mesh, shader and transform.

In Maya itself, a small interface is used to control the program if it is to send data or not.                       
![Image 5](Images/Shared_Memory_5.png?raw=true "Iamge 5")

A screenshot of how the program could be used: ![Image 1](Images/Shared_Memory_1.png?raw=true "Iamge 1")

# Most relevant files
The files that handle the actual Maya files for sending  are located in the "Sender/Inc" and "Sender/SRC" folders. For the actual receiving of the program, the most relevant files are in the following folder "Shared Memory/Reciever". There are a total of three files shared between the programs and they can be found under "Shared files".
