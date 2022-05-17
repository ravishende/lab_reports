[Home](../index.md)

# Lab Report 3


### Streamlining ssh Configuration

First, I created and then put in the code for my config file, using:
 `touch` to create the file, `vim` to edit the new file, and `cat` to show it.

Here's the file with adding the code with `vim`

![Image](config_code.png)


Here's the commands run to modify the file and then show that it is saved with the modification. I chose to kept the alias as ieng6 because it's an easy to remember name that tells what server it is.  

![Image](config_code.png)


So, with that config file setup, we can now run the following command:

![Image](run_ssh.png)


And then, as you can see, it does the ssh over to the ieng6 server without having to type out the entire username.

![Image](ssh.png)


Next, I created a new file on the client side using `touch newFile.txt`. From there, I copied it over to the server side using the following scp command:

![Image](scp.png)

As you can see, the text there that says `newFile.txt` shows that the file got copied over.


Next, once I ssh over to the server to see the results, it shows that the newFile.txt successfully got transfered over. 

![Image](scp_results.png)




### Setup Github Access from ieng6



### Copy whole directories with scp -r



