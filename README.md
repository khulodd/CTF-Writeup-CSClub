# UJ CyberClub CTF 

In the UJ CyberClub CTF, I participated in several challenges from different categories: Reverse, Steganography, Web, and Network. Here is a summary of the challenges and the steps I took to solve them:

## Challenge 1: Levi (Reverse)
- Analyzed an executable file and used the `ltrace` command to understand its behavior.
- Discovered that the program used the `strcmp` function to compare the input with the value "FZMUV90Q".
- Provided the correct input to obtain the flag.

## Challenge 2: CAN U HEAR ME?? (Steganography)
- Received an audio file and identified it as a steganography problem.
- Used Sonic Visualiser to analyze the spectrogram of the audio.
- Found the flag embedded within the spectrogram.

## Challenge 3: LetsWarmUp (Reverse)
- Examined a Python code that prompted for a password.
- Noticed that the password might be the value of `arg432`.
- Printed the value before the if condition to obtain the password and retrieve the flag.

## Challenge 4: Cookie (Web)
- Accessed a website and inspected its cookies.
- Discovered that the cookie value was encoded using base64.
- Decoded the cookie and modified the values to obtain the flag.

## Challenge 5: Flag leak (Network)
- Analyzed a pcap file using Wireshark.
- Searched for the word "flag" and found a base64-encoded text file.
- Explored further and discovered another text file with the correct flag encoded in base64.

In conclusion, participating in the UJ CyberClub CTF #2 provided an opportunity to explore various types of challenges and apply different techniques to solve them. Reverse engineering, steganography analysis, web exploitation, and network analysis were all involved. The CTF allowed me to enhance my problem-solving skills in the field of cybersecurity and exposed me to various techniques and tools used in different areas of the field.
