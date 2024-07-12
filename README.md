# MAC Address Changer

<h2>Description</h2>
This project covers 
MAC stands for Media Access Control. It is a permanent and unique address assigned to Network Interfaces by the device manufacturer. There are no 2 devices in the world that have the same MAC address. It is used within the network to identify devices and transfer data between devices. Each packet within the network contains a source MAC and the destination MAC.

Changing the MAC address will make you anonymous since it used to identify devices. It allows you to impersonate another device, and allow you to do things you might not usually be abelto do, such as bypass filters.
<br />

<h2>Distribution Used </h2>

- <b>Rocky 9.2</b>

<h2>Activity 1:</h2> 
In this activity, we will run through some commands related to user creation and deletion. I have segregated the entire activity into different sections so that it is easier to follow.<br/>
a. Create 3 users named operator1, operator2 and operator3. Set passwords for each of them, and confirm that it exists in the system.<br/>
b. Update operator1 and operator2 to include the comments "superman" and "batman" respectively.<br/>
c. Remove operator3 from the system. Confirm that this user no longer exist.<br/>

<h3>Part a</h3>

Add the users (follow the command below). Ensure that you are a root user. The password I used here for all accounts are "redhat", which is why there was a password warning. You'd definitely want to create a stringer password when creating new user, ideally a password with at least 12 characters that has uppercase and lowercase characters, numbers and special characters. <br/>
<img src="https://i.imgur.com/DHX91IA.png" height="80%" width="80%"/>
<br />
<br />
We can confirm that the users are created by checking the /etc/passwd file.  <br/>
<img src="https://i.imgur.com/bHd3dW2.png" height="80%" width="80%" alt="confirmation"/>
<br />
<br />
<h3>Part b</h3>
Now to update the comments for a couple of these users. Basically, this would be a brief comment, description or real name of the user. We can confirm that comments have been added. <br/>
<img src="https://i.imgur.com/fWaeC2l.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>Part c</h3>
Now let's remove operator3 from the system. We can confirm that the user is gone, and doesn't exist in the home directory as well.  <br/>
<img src="https://i.imgur.com/0goUgMt.png" height="80%" width="80%" alt="User Deleted"/>
<br />
<br />
<h2>Activity 2:</h2>
Now we will look at group management.<br/>
Create the "operators" group with a GID of 30000, add operator1, operator2 and operator3 users to the operator group and confirm that they are in the group.<br/>
Follow the steps shows in the screenshot:  <br/>
<img src="https://i.imgur.com/2lWdzU8.png" height="80%" width="80%" alt="Creation of group"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
