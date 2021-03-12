# caesar - 100 Points

## Description:
Decrypt this <a href="https://jupiter.challenges.picoctf.org/static/7d707a443e95054dc4cf30b1d9522ef0/ciphertext">message</a>. </br></br>
![image](https://user-images.githubusercontent.com/36644707/110899258-c2529d00-82ce-11eb-92fd-fdb6fe432fe5.png)


Hint: caesar cipher <a href="https://learncryptography.com/classical-encryption/caesar-cipher">tutorial</a>


</br></br>

## Solution

File has no extension associated at the end, lets see what kind it is.

</br>

Running 'file' on the ciphertext file shows that its ASCII text.

![image](https://user-images.githubusercontent.com/36644707/110899670-879d3480-82cf-11eb-8c0c-44915c9b1065.png)

</br>

Ran 'less' on 'ciphertext.txt' to reveal the flag in ciphertext.

![image](https://user-images.githubusercontent.com/36644707/110899890-df3ba000-82cf-11eb-80f6-feb083cc2a5b.png)

</br>

Using <a href="https://www.dcode.fr/caesar-cipher">dCode's Online Caesar Cipher</a> while testing all possible shift revealed that +4 was the key. 
The plaintext was disovered to be "crossingtherubicondjneoach".

![image](https://user-images.githubusercontent.com/36644707/110901213-f7acba00-82d1-11eb-8445-621f8a2b2497.png)

</br></br>

picoCTF{crossingtherubicondjneoach}
