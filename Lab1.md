# Bof 1
## Source code of Bof1
![alt text](./Image/bof1.png)
## Stack frame of Bof1
![alt text](./Image/image-2.png)
## How to do Bof1
![alt text](./Image/image.png)
Create bof1.out file
![alt text](./Image/image-1.png)
Get the address of the secretFunc
![alt text](./Image/image-3.png)
Use the address of the secretFunc to change the return address of vuln to secretFunc and we finish bof1
# Bof2 
## Source code of Bof2
![alt text](./Image/bof2.png)
## Stack frame of Bof2
![alt text](./Image/bof2stackframe.png)
# How to do Bof2
![alt text](./Image/bof2image.png)
Create bof2.out file
![alt text](./Image/bof2image2.png)
Use echo and check if you are on the right way
![alt text](./Image/bof2image3.png)
Now that we are on the right way change \x02 to \xef\xbe\xad\xde and we are finished with bof2
# Bof3
## Source code of Bof3
![alt text](./Image/bof3.png)
## Stack frame of Bof3
![alt text](./Image/bof3stackframe.png)

## How to do Bof3
![alt text](./Image/bof3image.png)
Create bof3.out file
![alt text](./Image/bof3image2.png)
Use objdump to get address of shell function
![alt text](./Image/bof3image3.png)
Now we use the address of shell function to change the func funtion to shell and we finish with bof 3