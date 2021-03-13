# Eighth Circle - 298 Points
Author: John Hammond

## Description:
Abandon all hope, ye who enter here...</br>
Download the file below.

Attachments:   <a href="https://ctf.nahamcon.com/files/6e0912abf579ae0172a3e662e5f3916d/eighth_circle?token=eyJ1c2VyX2lkIjozMzU1LCJ0ZWFtX2lkIjpudWxsLCJmaWxlX2lkIjoxMH0.YEwUDA.4ug4G_fBGKUvHmtw7fTlhqCJnVU">![image](https://user-images.githubusercontent.com/36644707/111014322-304fa080-8371-11eb-9535-1fa3f1573db9.png)</a>
</br></br>



## Solution:

Running file command on "eighth_circle" shows its an ASCII text, with very long lines, with no line terminators.

![image](https://user-images.githubusercontent.com/36644707/111015099-216aed00-8375-11eb-87d2-c3323c767c8f.png)


Renaming eighth_circle to eighth_circle.txt shows us the ASCII test.

![image](https://user-images.githubusercontent.com/36644707/111015246-def5e000-8375-11eb-8f04-27ff0681f4c5.png)

Now, let's open it in vim.

![image](https://user-images.githubusercontent.com/36644707/111015269-f339dd00-8375-11eb-802f-32c40c87f9db.png)

```
D'`r#LK\[}{{EUUTet,r*qo'nmlk5ihVB0S!>w<<)9xqYonsrqj0hPlkdcb(`Hd]#a`_A@VzZY;Qu8NMRQJn1MLKJCg*)ED=a$:?>7[;:981w/4-,P*p(L,%*)"!~}CB"!~}_uzs9wpotsrqj0Qmfkdcba'H^]\[Z~^W?[TSRWPt7MLKo2NMFj-IHG@dD&<;@?>76Z{9276/.R21q/.-&J*j(!E%$d"y?`_{ts9qpon4lTjohg-eMihg`&^cb[!_X@VzZ<RWVOTSLpP2HMFEDhBAFE>=BA:^8=6;:981Uvu-,10/(Lm%*)(!~D1
```
</br>
"eighth_circle"  I did a search of that and found it is in reference to <a href="https://en.wikipedia.org/wiki/Malbolge">Malbolge</a>. It is a public domain esoteric programming language
invented by Ben Olmstead in 1998, named after the eighth circle of hell in Dante's Inferno, the Malebolge.

Looking up the example programs on the wikipedia and I immediately found some similarities in the syntax/language. I then searched for a Malbolge interpreter.

<a href="https://malbolge.doleczek.pl/">Malbolge - interpreter online</a>
</br>

Erasing the field with the defualt text and adding the malbolge language from the challenge and hitting "Run" we get the flag.
</br></br>
![image](https://user-images.githubusercontent.com/36644707/111015705-43b23a00-8378-11eb-8d0f-3233bed9f9a4.png)
</br></br></br>


ANSWER:  flag{bf201f669b8c4adf8b91f09165ec8c5c}
