# PS4OfflineAccountActivator 9.00 ONLY!

Activates PSN account on jailbroken PS4 allowing you to export save data to USB among other things. The offsets are for 9.00 fw version. 

Requires [ps4debug](https://github.com/jogolden/ps4debug) to compile

Requires [MetroModernUI.1.4.0.0](https://github.com/dennismagno/metroframework-modern-ui) to compile

![Screenshot of the program](https://github.com/sjdo/PS4OfflineAccountActivator/blob/master/screenshots/ps4_4.png)

## Notes & Warnings

It's better to use this program on a new account. If you use it on an old account (with saves and trophies) you'll encounter these problems:
1. You won't be able to use your old save files easily (the ones created before activation). They'll show as broken. Maybe you can recover them with [Playstation-4-Save-Mounter](https://github.com/ChendoChap/Playstation-4-Save-Mounter). 
2. You'll have to delete your trophies (via FTP) because they will be signed with the unactivated account and all the games you try to launch will error out.

I repeat, I recommend to use a fresh console account for the activation, but do as you wish...


## How to use

1. Launch ps4debug on your PS4 whit Payload Guest [Payload Guest](https://github.com/Al-Azif/ps4-payload-guest)
2. Launch this program on your computer
3. Type in your PS4 IP adress and click Connect
4. Click Get Users
5. Type the account id you want to activate on the proper text box. You can get your account id from the folder name of an exported save
![Account id](https://github.com/charlyzard/PS4OfflineAccountActivator/blob/master/screenshots/ps4_2.png)
6. Click Set Id & Activate
7. Click Get Users again to check if it was changed properly
8. If you used an old account with trophies then fix the problems in the Notes & Warnings section

## Credits

Made by Sjdo 
Based on [PS4OfflineAccoutActivator](https://github.com/charlyzard/PS4OfflineAccountActivator)

Thanks to jogolden for the great ps4debug and to all the PS4 scene for making this possible.
