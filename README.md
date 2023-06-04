# 
<p align="center">
<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgKl0ibA8S5ypPck_OeVzoO-TeLQdei-LAQymdntToxupUYBOapLvXAbMV8FjZJIKxxvuC8wARaCYGUmBu3auAwSK4zZW8euj7O9Scwz7jDJulPi3fnF4P6-tU1-kDE0ghkXZexlJ0ry0ZsxLVpCTd3kFu9PRQ2dcn6ykW3syDnhNrVVSa0Li-EVWu6/w640-h640/68747470733a2f2f6269742e6c792f33504238563835.png" width="200" height="200"/>
</p>
<h1 align="center">PD Runner</h1>
<h3 align="center">PD Runner is an unlimited trial launcher<br>to run Parallels Desktop on your macOS<br>Only for learning and research usage<br><br>
<a href="https://pdrunner.blogspot.com/">
<img src="https://bit.ly/3Ee49cs" alt="Tsunami App Download" width="200" height"auto"></a><br><br>


[🔴 ꜰᴏʀ ᴅɪsᴄᴜssɪᴏɴ ᴏʀ ɪssᴜᴇs ʀᴇɢᴀʀᴅɪɴɢ ᴘᴅ ʀᴜɴɴᴇʀ ᴊᴏɪɴ ᴍʏ ᴅɪsᴄᴏʀᴅ sᴇʀᴠᴇʀ 🔴](https://discord.gg/yHaHRCdMeR)
<h4 align="center">As you know the previous repository was taken down, this repo is temporary and may get<br>
DMCA Strikes anytime. So, it would be better to communicate and stay connected<br>
at Discord for future updates incase anything goes wrong again.</h4>
</h3><br>

## 📲 Screenshot
<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEi-rp9LtJP6eYXnwBtp0PpB7UqAs9z_cbgcPrudhdVLSNbLQWQYeE-gF0AwprJH96YRKQZS4pcbWY1RhIFWlfDRVBZtmayPsiYNOPSNA8rzVtem_1r-nIhVm95NxXFgOeiHKp85vZJrIcW6ulDOIS-0Fxahucmgj9Uvsl5wZ_l-2ZtkQACGryycGMGV/s16000/PD-Runner-01.png" width=100% align=center />  

## 🛠️ Usage Guide
- Download Parallels Desktop installer
- Download the “PD Runner.zip” file below
- Extract the zip file and get the “PD Runner.pkg”
- Run the .pkg file and complete the installation process
- Reinstalling PD is recommended if the above procedure fails

## ❓ Frequently Asked Questions

**1\. Why do I need to enter a password when first run?**

> Because of the new authentication measure introduced in PD 17.1.0, you need to bypass it by quickly switching the system time. A “Privileged Helper” needs to be installed on the system to change the time.  
> If you don’t do this, you will need to enter the password every time you start an VM.

**2\. Why do I get “Error: Already Patched”?**

<img src="https://camo.githubusercontent.com/e840f917e9e07ae38a5f7159b289ad044003ad8976de25755401c3fb2505346f/68747470733a2f2f626c6f676765722e676f6f676c6575736572636f6e74656e742e636f6d2f696d672f622f523239765a32786c2f4156765873456971643044716d4d6c6d703965316c663661535350496c574e72667632444f79485853553748372d366b6d6a6271627a61384c724f57323949494c476351376136343366314545686373736c594472436342323275666f39776f706c6f5168794c4c627a4b697166386a4d6a6878705845643441796d75694444497755585370645a75414f616b78514d6c5348624642787638426b53556c5a3771516963436d6f5f4a41444758583066345f61396147444972567478494556752f7331363030302f3230303538323038332d32646365633639322d313863622d343762342d396339652d6663616431653931393031352d6d6f6469666965642e706e67" width=300 />

> If you get such an error, please try re-installing Parallels Desktop with the latest DMG installer. No need of uninstalling, just install it on top of the already existing application. Once re-installed, repeat the patching procedure with “PD Runner.pkg” file.

**3\. Why does PD Runner start without any windows?**

> PD Runner is a menu-based application, it only show an icon in the menu bar for use after starting, and there is no main window.

**4\. Why do I get an warning while running or installing PD Runner?**

<img src="https://camo.githubusercontent.com/af80a20b0af8a435919f15d43f50442530f0588ab241780bd882b0cc022f3412/68747470733a2f2f626c6f676765722e676f6f676c6575736572636f6e74656e742e636f6d2f696d672f622f523239765a32786c2f4156765873456a6e6c56306d2d32736f3453546a44693455314f7a79764b664f436342614c56414c794546724137783065514f70663365363576564f62715443524f5837487070794e544f4a427566556a333456617378507736514562506b646f5f586b6c59694c496c593658484a63794346685a6939756d7734444b56334f564b6f75735a70686f7a4b654b42674c716d547a352d4f4e66595079364b6a336271704f3975455965426e555f4c643577454d56575f4d54467937486370416d2f7331363030302f3138343434363730332d32363936616634312d663632362d346466642d613561302d6234653534383635626431392d6d6f6469666965642e706e67" width=300 />

> If you get an error message as shown in the picture above please uninstall the PD Runner app from the Applications folder and then run the following command in Terminal as admin. Lastly, install the latest PD Runner app from the releases section of this repository and it will work normally again.

     sudo bash -c 'rm -rf /Library/PrivilegedHelperTools/com.lihaoyun6.PD-Runner-Helper && launchctl enable system/com.lihaoyun6.PD-Runner-Helper'
    

**5\. Do I need to change the VM to a specific name to use it?**

> No, PD Runner can automatically list the VMs in the current system automatically.

**6\. Why does it say that PD Runner is damaged?**

<img src="https://camo.githubusercontent.com/a7ea1e34ea87fab4a255388e61e07d4dd67afdc881ff37fa1521d3120f7e74a6/68747470733a2f2f626c6f676765722e676f6f676c6575736572636f6e74656e742e636f6d2f696d672f622f523239765a32786c2f4156765873456a6b57554931526d42755041326c58704551786a33664a6e776d5539394a6f5678486d79783142655945784f6447785944643279644c3076586c5831323475396632794c7368446b7673366f5058794532574a4e3165704f395963722d64726d7333596a4f71315a4a542d6f715076685579634b3358355a357a4f565764374f667376736a543046786d5433722d6e6465503264636b72426f766d737968617a33516259694d53643149417a4f452d75325764383257356236562f73313630302f556e7469746c656425323064657369676e2d6d6f6469666965642e706e67" width=300 />

> If you get a message as shown in the picture above then run the following command in Terminal as admin and the application will start to function normally again.

     sudo spctl --master-disable && xattr -cr /Applications/PD\ Runner.app
    

[](https://github.com/utsanjan/PD-Runner#%EF%B8%8F-credits)✒️ Credits
---------------------------------------------------------------------

[**Lihaoyun6**](https://github.com/lihaoyun6/) and [**MikeWang000000**](https://github.com/MikeWang000000/) originally made the PD Runner app for macOS. But the repository was taken down due to a DMCA takedown notice. Hence, the credits goes to them for creating this amazing application. You can read more about the DMCA takedown notice from [here](https://github.com/github/dmca/blob/master/2022/01/2022-01-19-parallels.md). And, also thanks to [**Somebasj**](https://github.com/somebasj/) for providing the patch files that solves the Virtual Machines frequently suspending issue.[ㅤ](https://icrack.day/pdfm)

[](https://github.com/utsanjan/PD-Runner#-contacts)📞 Contacts
--------------------------------------------------------------

For Queries: [My Instagram Profile](https://www.instagram.com/utsanjan/)  
[Check Out My YouTube Channel](https://www.youtube.com/DopeSatan)
