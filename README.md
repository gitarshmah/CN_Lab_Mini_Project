
# Computer Network (CEN 593) - Lab Mini Project 

## Problem Statement
- Write a socket program to implement TCP client and Server such that
    in a multiclient system Client4 can send message to server then that message is forwarded to Client1.

## Working
 > Open terminal and start the server.
 - For Linux/Mac user
    ```shell
    python3 server.py 
   ```
    
- For Window 
    ```shell
    python server.py 
    ```
> Now start the N client connections.

 - For Linux/Mac user
    ```shell
    python3 client.py 
   ```
    
- For Window 
    ```shell
    python client.py 
    ```
> To broadcast a meessage use `/all` tag before the message .
```
/all message
```
> To send a private message to any `k`th client use ``/ck`` tag before the message.
```
/c1 message
/c2 message
.
.
.
```


## This project is made from the collective efforts of 
- [20BCS014 Arshmah Saeed](https://github.com/gitarshmah)
- [20BCS062 Lal Bihari Pandey](https://github.com/xpandeyed)
- [20BCS063 Mohammad Kashif](https://github.com/M0hammad-Kashif)
- [20BCS065 Ravi Gowri Jaswanth Reddy](https://github.com/Jaswanthmy)
- [20BCS079 Vidip Ghosh](https://github.com/Vidip-Ghosh)







