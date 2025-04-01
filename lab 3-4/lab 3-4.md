<h1>
  🚀 LAB 3 - 4 🚀
</h1>

<h3>
  1. View the gedit man page.<br><br>
  2. Use the man -k ext4 command to find the command to tune ext4 file-system parameters.<br><br>
  3. Understand and demonstrate the use of brace expansion.
</h3>

<hr>

<h1>
  Solution : 
</h1>

<h5>
  Lab 3: 
</h5>

  1. Open the terminal and type:
     <i>
       man gedit
     </i>
     
     <img width="209" alt="image" src="https://github.com/user-attachments/assets/4769719c-3b4d-43af-9960-c9554465156c" />



  2. If the manual page is not available, try installing `gedit` first:
     <i>
       sudo apt update && sudo apt install gedit
     </i>
     
   <img width="366" alt="image" src="https://github.com/user-attachments/assets/a851f7b1-b05c-4c87-a5fe-b40b00786bba" />

 
  <img width="358" alt="image" src="https://github.com/user-attachments/assets/4a2bc2fc-e9a1-4152-aee9-c58ae4087e25" />





<h5>
  Lab 4:
</h5>

  1. To search for commands related to ext4, type: <br>
     <i>man -k ext4</i>
     <br>
     
 <img width="365" alt="image" src="https://github.com/user-attachments/assets/acedd025-3258-436b-ac8d-ed82fb8f3ff6" />



  2. To find the command to tune ext4 file systems, look for `tune2fs` in the output and check its manual page:
     <i>man tune2fs</i>
     <br>
     <img width="368" alt="image" src="https://github.com/user-attachments/assets/9c9ce34f-e32e-4c25-9698-26bed50e9afb" />



  3. Understanding Brace Expansion: <br>
     <i>echo file{1,2,3}.txt</i><br>
     Output:

     <br>
     <img width="202" alt="image" src="https://github.com/user-attachments/assets/9608be2b-4604-4f96-b68d-337237a134d3" />




  4. Using a sequence expression:
     <i>echo file{1..5}.txt</i>
     <br>
     <img width="356" alt="image" src="https://github.com/user-attachments/assets/27da186c-22f4-4e94-92fb-4c17104c0366" />

