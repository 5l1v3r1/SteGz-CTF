# SteGz CTF
Level : 2 [Medium]

Encryption algorithm :
1. [base64 -> gzcompress -> gzdeflate  -> gzencode]
2. [base64 -> gzdeflate  -> gzencode   -> gzcompress]
3. base64
4. hex
5. base64
6. [base64 -> gzcompress -> gzencode   -> gzdeflate]
7. hex
8. base64

Don't use any coded tools please?
I mean, code the exploit to decrypt this flag by ur self!
Good luck!

CTF by FilthyRoot - Sora Cyber Team || Jogjakarta Hacker Link
http://github.com/soracyberteam/

Need reference? : 
https://www.php.net/manual/en/function.gzdeflate.php
https://www.php.net/manual/en/function.gzcompress.php
https://www.php.net/manual/en/function.gzencode.php
https://www.php.net/manual/en/function.bin2hex.php
https://www.php.net/manual/en/function.base64-encode.php
https://www.php.net/manual/en/function.exif-read-data.php
