<h1>Web App Lab Set Up</h1>
Open <a href="https://ssh.cloud.google.com/cloudshell/editor">Google cloud shell</a><br>
Enter the following commands<br>
<code>
<br>	docker pull vulnerables/web-dvwa <br>
<br>	docker run --rm -it -p 6080:80 vulnerables/web-dvwa<br>
</code>
Then you have to click on web preview.
Click on preview on port 8080
Then change the url, replace 8080 with 6080
you will have the default DVWA
