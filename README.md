# Hybrid-Encryption-for-cloud-storage
This Repository is created for mini project 

How to Run?

-> Install Requirements.txt(install the things in requirements.txt file) and Run App.py 

Due to openness and multi-tenant characteristics of the cloud, the traditional security mechanisms are no longer suitable for applications and data in the cloud. Due to dynamic scalability, service and location transparency features of cloud computing models, all kinds of application and data of the cloud platform have no fixed infrastructure and security boundaries. In the event of security breach, it is difficult to isolate a particular resource that has a threat or has been compromised.  According to service delivery models of Cloud computing, resources and cloud services may be owned by multiple providers. As there is a conflict of interest, it is difficult to deploy a unified security measure. Our system provides a solution over all these problems with the solution of hybrid cryptography technique

Working:

1.	The user signs in if already registered, or signs up to register themselves by providing their details such as name, email id, phone number, password for account et cetera.

2.	The user then selects the file that is to be uploaded by browsing from local storage.

3.	The user then selects the encryption algorithm that they want to use. The proposed system provides the choice between using a combination of AES and RSA or AES and Blowfish.

4.	The selected file gets uploaded after getting encrypted using the selected encryption algorithm combination.

5.	The user also has the option of viewing the files that they have uploaded or have access to and downloading them.

6.	On selecting a file to download it, the user is sent the decryption key on their email id that was entered on registration or sign-up.

7.	Using this key, the user can download the decrypted or original file.

8.	The system also provides a comparison with respect to security between the two hybrid encryption algorithm combinations i.e., AES and RSA hybrid combination and AES and 
Blowfish combination.



