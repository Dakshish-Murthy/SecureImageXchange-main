# SecureImageXchange
- The project involves the creation of a client-server architecture where two terminals, namely 'server' and 'client', establish a secure connection. Through the implementation of Diffie-Hellman key exchange, a common secret key is generated and stored securely on both ends. This key serves as the basis for the encryption and decryption processes.

- Utilizing a Tkinter-based graphical user interface (GUI), users can select an image file for encryption or decryption. The selected image is then processed using the 3DES encryption algorithm, ensuring protection of the image data. Encrypted images can be securely transmitted over the network, maintaining confidentiality and integrity.

- (This project is done as part of our semester course and developed in team)


## Getting Started
- Clone the repository in to your pc.
- Setting up the Virtual environment.
  - Install virtualenv through the command 'pip install virtualenv'.
  - Create a virtual environment in your current directory for a project with the command: 'virtualenv virt'
  - Start the virtual environment by activating with the command: 'virt/scripts/activate'
- Install Requirements.txt using the command 'pip install requirements.txt'
- Go to directory.
  - start the server.py -> 'python3 server.py'
  - start the client.py in parallel in another terminal 'python3 client.py'
  - this will store the shared key in files
  - now run the interface_dh.py 'python3 interface_dh.py'
 

## Images
<img width="888" alt="image" src="https://github.com/kvishal2706/Recruitex/assets/96335442/927c66bd-c231-4150-bc61-d7a042981497">
<br>
<br>
<img width="381" alt="encrypted-success" src="https://github.com/kvishal2706/Recruitex/assets/96335442/25b170a1-18b2-4843-baf9-a2f6f810440a">
<br>
<br>
<img width="383" alt="decrytp-success" src="https://github.com/kvishal2706/Recruitex/assets/96335442/3fad3d37-9a3b-4854-be35-e4852e0c073f">
