# Change GoogleDrive mounted Drive name and logo

## Change Drive Name using a single .bat file in Windows
### Procedure
1. label ***Drive Letter*** : ***"Drive Name"*** (Eg: label D: Data)
2. Save as .bat
3. Run it

#### Useful to have a script when mounting Google Drive instead of renaming each drive everytime.

## Change Logo of a Drive
### Procedure
1. Open Regedit
2. Go to "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer"
3. Create a key called "DriveIcons" if it doesnt exist
4. Open "DriveIcons", so now the path is "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\DriveIcons"
5. Here create new keys for each Drive letter that you want to change logo. (Eg: Creating for Drive letter W, X, Y, Z)

   ![image](https://github.com/user-attachments/assets/48996eff-c5ad-41a9-bca1-4ae3a1924b6d)

6. Under each of the Drive Letter Keys create another key called "DefaultIcon"

![image](https://github.com/user-attachments/assets/25e9b2ac-3854-4c29-9272-81c4154627cf)

7. Double Click on the (Default)

![image](https://github.com/user-attachments/assets/b5d677d6-466b-4de0-8ae9-fcf8cfde8ff0)

8. Change the default value of (Default) of each "DefaultIcon" to the PATH where your icon is located. (Icon should be .ico file)

![image](https://github.com/user-attachments/assets/21e5e17e-8ea3-4a19-9e70-52c4d7a6ebce)

#### Automatically Uses the .ico file for these drives as soon as the Google Drive is mounted.

   
