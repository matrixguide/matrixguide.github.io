## Install / Login

1. Install Riot [Android](https://play.google.com/store/apps/details?id=im.vector.alpha) | [iOS](https://itunes.apple.com/us/app/vector.im/id1083446067) | [F-Droid](https://f-droid.org/packages/im.vector.alpha/)
2. Fill in username and password ([Guide to create account](https://madfedora.github.io/user)), then check **Use custom server options (advanced)**

![alt text](https://i.imgur.com/Z23iYeq.png "login")

3. Scroll down and fill in (**https://disroot.org** *Not matrix.disroot.org*):

![alt text](https://i.imgur.com/8fbGPP1.png "Custom server")

4. This is how the user page look like

![alt text](https://i.imgur.com/OfebblI.png "User page")

## Add User

1. Click the *Plus Circle at the right bottom*, click **Start Chat**

2. Enter username you want to search, click the Plus to add user to chat

![alt text](https://i.imgur.com/5Ps80wR.png "Start Chat")

## Verify Fingerprint

To read, send or receive encrypted message you must first verify the keys of user. (and vice versa) They should exchange the fingerprints with you to confirm they are the person you communicate to. An example of fingerprint is ***APOCJNQLMB**, each fingerprint is unique and exact 10 characters*. *You should also verify the **device key***

1. In the room, select the option then **Room Details**

![alt text](https://i.imgur.com/9Nrl1d8.png "Room Details")

2. Click on **Show Device List**

![alt text](https://i.imgur.com/tEwUrXw.png "Device List")

3. When you are sure the person had the **correct device ID and Key**, click **Verify**

![alt text](https://i.imgur.com/c60sn70.png "Verify Devices")

4. It will ask you to confirm the key, device ID and its fingerprint. When ready, click **I Verify That The Keys Match**

![alt text](https://i.imgur.com/kwKo8Gq.png "Confirm ID")

5. Now their key is verified. **You should see the lock** instead of the warning sigh. To *Unverify* click it again.

![alt text](https://i.imgur.com/U4jR2yE.png "Verified")

## Import / Export Room Key

Every time you log out or sign in, the room will generate new key, meaning *you will not be able to read message from previous session **unless you have the E2E room key.***

1. You can export the E2E key by go to **Settings**. Click **Export E2E room keys**

![alt text](https://i.imgur.com/Y9c7Dfe.png "Export Room Keys")

2. Fill in your password and click **Export**. It will download your key into Downloads folder with name **riot-keys.txt**

![alt text](https://i.imgur.com/a8FiGo8.png "Export")

3. To import, the steps are the same. Click **Import E2E room keys**, fill out the password and select location of **riot-keys.txt**

### To see [tips and troubleshooting](https://madfedora.github.io/tips)
### Back to [Index](https://madfedora.github.io/)
