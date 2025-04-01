<h1>
     Experiment 1 - 2 
</h1>

<h3>
    1. Create the operator1 user and confirm that it exists in the system. Set the password for operator1. Create the additional operator2 and operator3 users. Set their passwords as well.
    <br><br>
    2. Run the usermod -c command to update the comments of the operator1 user account. Remove the operator3 user from the system.
</h3>

<hr>

<h1>
    Solution :
</h1>

<h5>Lab 1:</h5>
<p>1. Open the terminal and type:</p>
<i>sudo useradd operator1</i>
<br>
<img width="284" alt="image" src="https://github.com/user-attachments/assets/9597b449-aa3d-4a94-becb-410dd4fd2980" />



<p>2. To check whether or not the user is added:</p>
<i>sudo cat /etc/passwd</i>
<br>

<p>At the end of the file, you will be able to see:</p>

<p>3. To add the password:</p>
<i>sudo passwd operator1</i>
<br>
<img width="371" alt="image" src="https://github.com/user-attachments/assets/8b443778-cbc3-4144-8c56-7c42cb282c08" />



<p>4. Follow the same steps for operator2 and operator3 as well:</p>
<img width="362" alt="image" src="https://github.com/user-attachments/assets/e3ba80b7-c964-47a5-bc0c-d91d02756d31" />
<br>
<img width="368" alt="image" src="https://github.com/user-attachments/assets/21f96507-cc56-4803-af8a-3a3f0a41b46c" />




<h5>Lab 2:</h5>
<p>1. To add comments to a particular user, type:</p>
<i>sudo usermod -c "Operator1's comment" operator1</i>
<br>
<img width="367" alt="image" src="https://github.com/user-attachments/assets/06e72ff0-8a41-4bf4-ad62-9f8da7f90d31" />


<p>2. To delete the user:</p>
<i>sudo userdel -r operator</i>
<br>
<img width="350" alt="image" src="https://github.com/user-attachments/assets/cf72b1a5-b680-43c2-a20a-7caa00f6c57e" />



<h5>Creating Practice Files and Directories:</h5>
<p>Use the <i>touch</i> command to create sets of empty practice files:</p>
<i>touch song{1..6}.mp3 snap{1..6}.jpg film{1..6}.avi</i>

<p>Use a single command to create all three subdirectories:</p>
<i>mkdir friends family work</i>
<br>
<img width="353" alt="image" src="https://github.com/user-attachments/assets/d0e2578e-eb82-4d6c-9f20-b7c907a824b4" />

