# Online Banking Management System(OBMS)

This project aims to develop a online banking system that is user-friendly and multi-functional.

## How to use OBMS ?

1.Compile and run ``` init.c ``` file which will initialize all the files required for this project. It will also create a login file named ``` login_info ``` which will contain administrator username and password. By default, credentials for Admin are stored as:

Username : ``` Admin ```
Password : ``` admin@1234 ```
(Note: All username and password are case sensitive)

```bash
$ gcc init.c
$ ./a.out
```
2.Compile the Server and Client:

```bash
$ gcc server.c -o server
$ gcc client.c -o client
```
3.Run the server in one terminal instance:
```bash
$ ./server <PORT NO.>
```
For example: ./server 9768

Run the client in different terminal instance:
```bash
$ ./client <IP ADDRESS> <PORT NO.>
```
For example: ./client 127.0.0.1 9768


After running client, login as Admin first and start creating accounts for the customers.
(NOTE: There is a session check running in the program. So, one user can login only from one window.)
