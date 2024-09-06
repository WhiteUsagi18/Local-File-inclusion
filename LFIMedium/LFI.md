# What is a Local File Inclusion (LFI) vulnerability?
Local File Inclusion (LFI) allows an attacker to include files on a server through the web browser. This vulnerability exists when a web application includes a file without correctly sanitising the input, allowing and attacker to manipulate the input and inject path traversal characters and include other files from the web server.
<br><br>
The following is an example of PHP code vulnerable to local file inclusion.

