# What is a Local File Inclusion (LFI) vulnerability?
Local File Inclusion (LFI) is a type of vulnerability found in web applications where an attacker can manipulate a web application's file inclusion functionality to include files from the server's local filesystem.
<br><br>
The following is an example of PHP code vulnerable to local file inclusion:

![image7](./img/image7.png)

In this write-up we will go through on how to exploit LFI vulnerability.

# Identifying Vulnerabilities
This will be our target site for LFI attack.

![image 1](./img/image1.png)

This site looks normal right? But if we take a look closely, there are 3 buttons and each button has its own page number. If we try to click any of the buttons, we will notice that in the url, there are something that has been added.

![image 2](./img/image2.png)
