<h1>Template</h1>

 ### [YouTube Demonstration](https://youtube.com)

<h2>Description</h2>
How to get wifi password once you have the .cap file.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Kali Live(64-bit)</b> 
- <b>Aircrack-ng</b>

<h2>Environments Used </h2>

- <b>kali-linux-2022.2-live-amd64</b> (21H2)

<h2>Walk-through:</h2>

<p align="center">
1. <br/>
Once you have the .cap file fire up Kali and open a terminal. Unzip rockyoutext.txt.gz "sudo gzip -d /usr/share/worldlists/rockyou.txt.gz". You should now have a rockyou.txt file.
<br />
<br />
2. <br/>
In the terminal type "aircrack-ng filenamehere.cap -w /usr/share/wordlists/rockyou.txt" and press enter. If the password is in this wordlist you will get a "KEY FOUND !". This wordlist consist leaked passwords.
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
