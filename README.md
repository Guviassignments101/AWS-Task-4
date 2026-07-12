# AWS-Task-4
Launch an EC2 instance (Linux and Windows) along with a web server. Then, create an EBS volume of 5 GB, attach it to an EC2 machine (Linux and Windows), and take a snapshot. Finally, create an EBS volume using the taken snapshot.

Step 1: Launch the Ubuntu EC2 Instance with HTTP accesson port 80 
<img width="1917" height="762" alt="image" src="https://github.com/user-attachments/assets/36a42806-c398-42fc-ae0b-cf9b9978da9e" />
<img width="1912" height="756" alt="image" src="https://github.com/user-attachments/assets/ea45bdf6-bfaa-42a4-8fdf-4434f328b4cc" />

Step 2: Update ubuntu install start enable and check status of apache
<img width="1897" height="761" alt="image" src="https://github.com/user-attachments/assets/89f6525d-18b2-4a22-932a-5aa948491031" />
<img width="1902" height="968" alt="image" src="https://github.com/user-attachments/assets/4c66a32c-0975-4ff3-8286-7c31f83309db" />

Step 3: Create a 5 GB EBS Volume
<img width="1872" height="757" alt="image" src="https://github.com/user-attachments/assets/00d24e70-61df-4b43-854e-b13f40d0a865" />
<img width="1621" height="333" alt="image" src="https://github.com/user-attachments/assets/5c90a624-3f0f-4657-a7aa-163d0eed538d" />

Step 4: Attach the Volume to instance
<img width="1872" height="761" alt="image" src="https://github.com/user-attachments/assets/f5926114-beeb-4581-b720-eeb06216a831" />

Step 5: Verify attached Disk
<img width="1918" height="758" alt="image" src="https://github.com/user-attachments/assets/e42e637d-a823-46f6-943b-a7f03919353b" />

Step 6: Format the volume
<img width="1908" height="460" alt="image" src="https://github.com/user-attachments/assets/516d3c95-c5f0-41f4-8895-383cd71dc7a3" />

Step 7: Create Mount directory and mount volume to it
<img width="1900" height="547" alt="image" src="https://github.com/user-attachments/assets/da1b8a9e-7f63-43fc-b4a3-78b2439aec59" />

Step 8: Store Data and check
<img width="1907" height="426" alt="image" src="https://github.com/user-attachments/assets/3988d8a4-1e3f-4c22-9105-9f0a854e2027" />

Step 9: Create Snapshot
<img width="1907" height="737" alt="image" src="https://github.com/user-attachments/assets/af1a909a-b693-4bdd-b4ed-6375bf7f2530" />
<img width="1907" height="748" alt="image" src="https://github.com/user-attachments/assets/6252791d-4648-4619-8163-d351ded2c9dd" />
<img width="1892" height="756" alt="image" src="https://github.com/user-attachments/assets/3bf8acdb-b8d8-422c-bc69-2245732f5e1d" />

Step 10: Create a New Volume from snapchat
<img width="1907" height="767" alt="image" src="https://github.com/user-attachments/assets/cce227a0-09c0-4db7-bc05-8b3614b6f8ce" />
<img width="1897" height="767" alt="image" src="https://github.com/user-attachments/assets/1bca3878-c32f-4993-b958-b65399a0d59a" />
<img width="1906" height="438" alt="image" src="https://github.com/user-attachments/assets/cd9d079c-6f47-4e77-874d-465569166d51" />

Step 11 Verify the Snapshot
Attach volume to EC2
<img width="1897" height="738" alt="image" src="https://github.com/user-attachments/assets/f572ccbd-49ae-44d0-991e-f61593d7b334" />
<img width="1906" height="395" alt="image" src="https://github.com/user-attachments/assets/c2474f7c-f520-4dc1-b0db-83b758427830" />

Step 12: Create Mount directory and attach  volume to directory 
<img width="1892" height="531" alt="image" src="https://github.com/user-attachments/assets/d55c50b0-ce97-4ea3-b197-2897cec832d8" />



