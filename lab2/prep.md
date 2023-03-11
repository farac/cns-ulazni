# Lab Title: [Insert title here]

## Challenge Answers

- **Challenge 1:** [Insert answer here, i.e., a Chuck Norris fact]
- **Challenge 2:** [Insert answer here, i.e., a `password` to unlock the next lab]

## Other Relevant Information

[Insert here, if applicable]
  
## Lab Prep Questions and Answers

1. What is the _Address Resolution Protocol (ARP)_, and what is its role in a network?
    - ARP or Address Resolution Protocol is a communication protocol used to discover link layer adresses, associated with a given internet layer address. (e.g. MAC to IPv4)
  
2. What is a _Man-in-the-Middle (MitM)_ attack, and how does ARP spoofing enable it?
   - A type of attack where the attacker inserts itself into the method of communcation. ARP can be exploited by spoofing ARP responses.

3. How does an attacker use ARP spoofing to intercept network traffic?
   - The spoofed response claims that the correct MAC adress for the wanted IP address is on a system belonging to the attacker.
  
4. How is the _cookie_ used to derive the encryption/decryption key?
   - ?

5. What REST API request do you need to send to the _crypto oracle_ the secret cookie?
   - GET /arp/cookie
  
6. How do you obtain the authentication token?
   - By requesting it from the crypto oracle server with correct credentials.
  
7. How do you use the authentication token to obtain the cookie?
   - It's needed as part of the request to the server.

8. What encryption mode is used to encrypt the challenge in this lab?
   - AES-CBC

9. What tool can you use to capture network traffic on a local network interface?
    - tcpdump
