# OverTheWire Bandit Level 10

## Objective

OverTheWire Bandit Level 10 introduces decryption techniques to retrieve the password for the next level. This level is designed to help users become familiar with encryption and decryption, particularly `base64` encoding in this instance.

### Skills Learned

- Decrypting encrypted data
- How to use CyberChef

### Tools Used

- Linux terminal
- CyberChef
- `cat`, `ls`, `base64`, `ssh`

## Steps

*Reference 1*

![Screenshot 2024-10-03 004544](https://github.com/user-attachments/assets/e2491baf-bdc7-4956-9bd9-0e9a5c814ded)

While not as difficult or time-consuming as other levels, such as Level 12 or 20, it introduces another important and prevalent concept in cybersecurity: encryption and decryption. The first step was to find the data within the directory containing the encrypted password using the `ls` and `cat` commands.

*Reference 2*

![Screenshot 2024-10-03 004626](https://github.com/user-attachments/assets/93419550-2701-4a13-b576-6f9138f2b27e)

 After receiving the `base64` encoded data, I went to a website named CyberChef and plugged the data into the `base64` machine. The output provided was the decrypted message shown in *Reference 2*, providing me the password for the next level.
