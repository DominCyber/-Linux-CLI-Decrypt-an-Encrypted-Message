# Decrypt an Encrypted Message
## Objective
Coursera Google Cybersecurity Professional Certificate Course work intend to impart practical cybersecurity skills. This guided project utilizes a virtual enviroment to rapidly familiarize users with Linux CLI for decrypts an encrypted message and cryptography.

### Skills Learned
-CLI Commands
<p>--For displaying hidden files in a directory (-a)</p>
<p>--Translation of encrypted text via mapping (tr)</p>
<p>--Translation of encrypted text via mapping (tr)</p>
<p>--Securing decryption output and key use (see below)</p>
<p>--Argument for decryption (-d)</p>
<p>--Specifying input and output file name arguments (-in, -out)</p>
<p>--Specifying decryption process password (-k)</p>
<p>-Exploring cryptograhic standards for decryption out</p>

### Tools Used
-Laptop
<p>-Coursera Google Cybersecurity Professional Certificate Course</p>

### Steps
<img src="https://i.imgur.com/nZx9XLn.jpg" style="width: 65%;" alt="1">
<p><i>Linux CLI decryption example</i></p>
/caesar$ hidden files are revealed with "ls -a". The hidden file, hidden status indicated with a "." prefix, displays an encrypted message with the "cat" command.
The output was encryped with a caesar cypher, with is then translated with the "tr" command and displayed. The command is accompanied with mapping parameters; the "d-za-cD-ZA-C" indicates that the original message alphabet range will be translated to the second parameter values. Lastly, the following commands specify: "openssl aes-256-cbc" for a secure output; "-pbkdf2" for secure key method; "-a" for encoding the output; "-d" for decryption; "-in ... -out..." input and output file name; and "-k" for password for decryption.
