# Project 5 - Encryption

Time spent: 4 hours spent in total

## User Stories

The following **required** functionality is completed:

1\. Symmetric Encrypt/Decrypt
  * [*]  Required: Repair the symmetric encrypt and decrypt code

2\. Encrypted Message 1
  * [*]  Required: Decrypt the government message
  * [*]  Required: Encrypt a response and include in this README

3\. Generate Public-Private Keys
  * [*]  Required: Repair the key generator code
  * [*]  Required: Generate keys for "johnsteed" and add him to the Agent Directory

4\. Asymmetric Encrypt/Decrypt
  * [*]  Required: Repair the asymmetric encrypt and decrypt code

5\. Create/Verify Signature
  * [*]  Required: Repair the create and verify signature code
  
6\. Encrypted Message 2
  * [*]  Required: Decrypt the message
  * [*]  Required: Verify the message
  * [*]  Required: Include a response message in this README

7\. Agent Messages
  * [*]  Required: Repair the dropbox code
  * [*]  Required: Repair the messages area
  * [*]  Required: Display encrypted messages for all agents
  * [*]  Required: Messages indicate whether the message signature is valid
  * [*]  Required: Your messages are automatically decrypted

8\. Identify the Double Agent
  * [*]  Required: Decrypt as many email messages as possible
  * [*]  Required: Identify the double agent: Natasha

The following objectives are **optional**:

* Bonus Objective 1\.
  * [ ]  Track down the bugs in the code and fix them.

* Bonus Objective 2\.
  * [ ]  Write a report of your discoveries (longer than 300 characters).
  * [ ]  Compose a secure email for sending over an insecure network.
  * [ ]  Include the email with your encrypted report in this README.

* Bonus Objective 3\.
  * [ ]  Add a "Create/Verify Checksum" section to the Encryption Tools area.

* Advanced Objective 1\.
  * [ ]  Add support for other symmetric algorithms.

## Video Walkthrough

Here's a walkthrough of implemented user stories:
<img src='http://i.imgur.com/zLvdlLP.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Objective 2:

Decoded message: I heard about your current situation. Do you know who hacked APEX? -- The Chairman

We are currently investigating the situation. We will update you ASAP. --agent99


F4c3DbpkMTylBdcMI6Rx0Qz96C0Iwdz8duR/03H9voh3JPSZXrE2cni74EUT0J791lTa7On/H9bqNYgGKZmpympeew0eQd8BZupKWLwlvi+PTnsCjVgcMTHhsqyKcGvFH43NbxYFleC49tSa/OC6gQ==


Objective 6:

		Cannot access APEX from this location. Send new agent codename and public key 
		so I can contact. Encrypt response to protect codename. 
		Include signature to verify identity and message integrity. -- sydneybristow

		The message signature is valid. Your new codename will be red five. Public key will be 
		sent soon.
		
		Encrypted:
		AylqDVH6Nxr8sMLQYa0R85kMoo4liob5qSnd8F7IzBv7xs9Lc7ol4DZEGoZcor2CbrCkSg40ZcTOGQTgd099jqxZgUcd41AhS9wFvfkk0ghUPbZgQtbjRzeUk/rEaaiwzwu7yQI/uBCGmdqy6OAQq41ELN1ogS7fmgDhJRDB8tfZhwmzolk5B+rG20rJCACNTRNIYS4YK0QxxdcM+ppRuQ0lFyJojTV14wQMbBix6ON9p83Q1wel97sapNJLyCurm7nYqPZyfPFHuaLSM1J561cXo60JpwQEi2vAQYI6pEb78zNxK2u3zFGquoxckFe0uPYHCtoRi3e28sr2tW0SFw==
		
		Sig:
			H8X1z9lY6yIPDCyvRVBPPuuLeqaTM0ko0C0HXuiY/9XhrcFyJC7m84h67Ag1Kl2d4jMRlZXWgiL+wq5gtbSfBbxG2QqfzHlYvtq2bdVY0Uz/THdrPv4cusM08mxkFBBiKJvwyh36De+2eq0vP2s4MCpWcabb6y+QksOXNgRxS7pW7CBvyLFGw5N6lsCMqqhL3sONANPJ5G9sRJw4ehL3Ty5/NMSCYDJg5WeNSIQrCd2mNjAnqdmFO1vV4xtZTJyDfHL962kp4dxgy8bfFo9GZ2f/v8G85vsrmrOKi8H/CWrvB6GW/0WJec/0sAtQss3WBo3sIfPtsBuIXJeb6WxpqA==

## License

    Copyright [2017] [Joseph Bennett]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
