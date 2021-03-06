# Lab Report 3

## Streamlining ssh Config

1. I edited my .ssh/config file with my Macbook's terminal
![Image](./images/sshconfig.png)

2. I was able to logon to server using the new alias.
![Image](./images/lab3-sshlogin.png)

3. Example of using scp to copy files with the new alias.
![Image](./images/lab-3-scp.png)

---

## Setup Github Access from ieng6

1. The public key I generated is stored on my Github account and user account(~/.ssh).
![Image](./images/githubkey.png)
![Image](./images/ieng6pubKey.png)

2. The private key is stored on the user account as well (along with public key).
![Image](./images/ieng6keys.png)

3. Now, I tried running git commands on server. First, I cloned one of my repo to my account, and ran the following command
![Image](./images/gitcomm1.png)

4. As shown, a "new line" appeared at the end of the java file.

5. Then, I used "git status" to check if it's modified and commit & push the changes. 
![Image](./images/gitcomm2.png)

6. Here's a link for the resultant modification:
[Click Here](https://github.com/soph-song/Demo1/commit/d8194a4312e791296a31804c88704a0a39bb366b)

---

## Copy whole directories with scp -r

1. I copied the whole directory onto my server using "scp -r"
![Image](./images/scpMDP.png)

2. Now, I login to my account, compile and run the test on the server
![Image](./images/JunitMDP.png)

3. Doing step 1 and step 2 in one shot (It's a long list of files that were uploaded, so I'm going to show part of it, then the part where Junit successfully runs)
![Image](./images/lab3P3.png)
![Image](./images/lab3P3b.png)
