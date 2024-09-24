# CTF
## Source code of ctf
![alt text](./Image/ctf.png)
## Stack frame of ctf
![alt text](./Image/ctfstackframe.png)
## How to do ctf
![alt text](./Image/ctf1.png)
Create ctf.out file
![alt text](./Image/ctf2.png)
Now we use objdump to get address of myfunc function
Then we use gdb -q ctf.out and make a breakpoint at myfunc
![alt text](./Image/ctf5.png)
According to the code we see that  in myfunc there is a check for the file flag1.txt and if we try to overwrite it at this moment this will happen
![alt text](./Image/ctf3.png)
So to avoid it we need to create a flag1.txt
![alt text](./Image/ctf4.png)
Now we can use myfunc
But we need to to see where the p and q of my func are, to do that we need to use disas myfunc to know where it is after doing that we will have these results
![alt text](./Image/ctf6.png)
![alt text](./Image/ctf7.png)
Use r echo to change return adress  of vuln to myfunc
![alt text](./Image/ctf11.png)
![alt text](./Image/ctf8.png)
Now we will need to set p and q value
![alt text](./Image/ctf9.png)
![alt text](./Image/ctf10.png)
And we are finished