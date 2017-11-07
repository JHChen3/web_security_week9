# web_security_week9

# Which Honeypot(s) you deployed
The honeypoy I deployed is Dionaea, Snort and glastopf.

# Any issues you encountered
In the beginning, I found it is not enough to complete this assignment by following the instructions on the Codepath website. I had a hard time in creating MHN VM. Fortunately, I have found a solution on Discussion Board.

# A summary of the data collected: number of attacks, number of malware samples, etc.
There are 1935 attacks in total.
Here is a gif showing the attacks detected.
https://user-images.githubusercontent.com/21267287/32472172-43e85c50-c32f-11e7-9fee-91cbf8aac1e7.gif
The number of attacks detected by Dionaea sensor is 1824, The number of attacks detected by Snort sensor is 109, The number of attacks detected by glastopf sensor is 2.
It seems like the number of attacks detected by Dionaea sensor becomes 1825 when the gif goes on, but I still keep 1824 since the json file I have uploaded only has 1824 attacks by Dionaea.

As the number of attacks indicated, Dionaea sensor frequently detected attacks, while the other two did not. Especially glastopf sensor, which spent several hours to detect only 2 attacks.

# Any unresolved questions raised by the data collected
I did use nmap to testify the honeypots, but I can only see the attacks detected by Dionaea and Snort, I wonder why glastopf sensor doesn't detect any attacks.
