![chall](image-1.png)


This one is a bit tricky. 

![given](image.png)

After clicking 'Start the Challenge,' I received the following text. And based on my observation, it appears to be encoded in hexadecimal. To decode it, I visited Cyberchef.

![decode](image-2.png)


After decoding it, I obtained what seems to be an HTTP header. Considering the provided resources, it appears that the focus should be on 'authorization.' So, I copied the value of the authorization, which seems to be in base64 format. Upon decoding it, I found the answer.

![answer](image-3.png)