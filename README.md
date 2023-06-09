Directory Traversal Attacks

Directory traversal or Path traversal attack is web security vulnerability, using this this vulnerability an attacker can read arbitrary files on the server that is running an application.

Attacker can get the application code and data, sensitive information like credentials for back-end systems, and sensitive operating system files. 

There are the cases where in an attacker was able to write in files on the server. Attacker was able to modify application data and he was able to take full control of the server. That is dangerous .

Here is the example of directory traversal attack, when DT vulnerability is present in the application then attacker can use [filename=../../../etc/passwd] in the url path to read from the following file path: /var/www/images/../../../etc/passwd


Let’s have a look into real time example:

The testphp.vulnweb.com is the vulnerable website provided by Acunetix

When you access below website and it path /cvs/

http://testphp.vulnweb.com/CVS/

You are able to access their files which are on their server and nobody from outside should have access to these sensitive files:
<img width="283" alt="image" src="https://github.com/archanaheeralal77/Directory-Traversal/assets/127080874/f601caa7-b063-43cf-996d-f55cd339c6ad">

<a href="workspace.xml">workspace.xml</a>                                      20-Apr-2012 08:23               12473
