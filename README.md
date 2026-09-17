# CatS22FlipGuide-Tips
Tips for the Cat S22 Flip
# Fixing keypad.
The keypad starts to have sensativity issues after extended use. 
The issues can either be fixed by
1. downloading and installing [this apk](https://github.com/Qar-Kain/CatFix/releases/tag/v1.0.20032025) once your Cat S22 is rooted. (PS: choose the apk without bluetooth)
2. Or by following [this guide](https://www.ifixit.com/Guide/CAT+S22+Flip+Keypad+Replacement/199702)
3. The best way I have found is applying heat to the edges of the silicon pad of the keypad, and then wedging a small flat-head screwdriver in between the space of the silicon keypad and the rest of the case till you separate the silicon pad from the rest for the case, then applying epoxy adhesive to the edge of the silicon pad and placing it back in the case fixing the problem permanently.
# Quicker animations and smoother expierence
I find that removing animations speeds the phone up alot.
you can speed up or remove animations 2 ways:
1. To fully remove animations navigate to 'Settings>Accessability>Remove Animations' and enable 'Remove Animations'
2. If you still want animations but you want them to be faster then navigate to 'Settings>System>Developer Options' and there will be 3 diffrent animation options; 'Window animation scale', 'Transition animation scale', and 'Animator duration scale'. Each of those 3 options are set to 'animation scale 1x' by default. change the scale to .5x for each of the 3 options individually and try them out till you find which animation speed you like best for each.
# Device Navigation with keypad
1. To open app drawer on home screen with keypad double-press the home button.
2. To open quick-settings with keypad press and hold the recent apps button.
3. To speed dial on home screen press and hold any the numbers 1-9 on homescreen. It will ask you to assign a phone number for the key you pressed, and click yes and then assign a phone number. (key 1 is already assigned to voicemail)
4. To remove an apps from recents in the recent apps dailog press the 'UP' button and then press the C/Clear button to remove the app from recents.
# Debloating, Degoogling, Rooting. 
1. Follow [this guide](https://xdaforums.com/t/tut-root-how-to-root-cat-s22-flip-on-version-30.4626971/) to root your phone.
2. Afterwards, follow [this guide](https://forums.jtechforums.org/t/kitty-rom-small-cat-super-debloated-with-android-auto/) to install a custom debloated rom.
3. Once you installed the rom, setup the phone WITHOUT CONNECTING TO THE INTERNET.
4. Download the 'Magisk-V30.7.apk' from [here](https://github.com/topjohnwu/Magisk/releases/tag/v30.7).
5. Copy the apk from your computer onto your phone and install it.
6. Open the Magisk app and it will reboot your phone.
7. After magisk rebooted your phone, go back into the magisk app and go to the magisk settings.
8. Within the magisk settings press 'Systemless host' and enable zygisk and press 'enforce deny list'.
9. Exit the magisk settings and reboot your phone
10. I created A magisk module to debloat and degoogle your phone even more after you've already installed the kitty rom and rooted your phone. I created 2 versions of the magisk module. 1 version has google messages installed and the other version has the default andriod 11 messaging app installed. If you want google messaging download [this](https://github.com/rozeraize/CatS22FlipGuide-Tips/blob/main/degoogled-module/google-messaging.zip) zip file. If you want the plain android messaging app download [this](https://github.com/rozeraize/CatS22FlipGuide-Tips/blob/main/degoogled-module/non-google-messaging.zip) zip file.
12. copy the zip file you downloaded from step 10 onto your phone.
13. open the magisk app, navigate to the modules section, click 'install from storage', then choose the zip file that you downloaded.
14. After magisk installs the zip file as a module restart your phone.
15. NOW YOU CAN CONNECT YOUR PHONE TO THE INTERNET.
16. Download [this magisk module](https://github.com/Xenoxis/magisk-disable-logd/releases/tag/v1.0.1) and copy it and install it onto your phone for a slight performance boost.
17. Download [this magisk module](https://github.com/symbuzzer/Volte-Wifi-Calling-Enabler/releases) and install it onto your phone to enable volte wifi calling.
18. Download and install [this magisk modules](https://github.com/KOWX712/PlayIntegrityFix/releases).
19. Reboot phone
# Installing microG services and android auto. (Note: this only works if you already did the 'Debloating, Degoogling, Rooting' section)
1. download and install [this magisk module](https://github.com/LSPosed/LSPosed/releases) (Note: Download the zygisk release, not the riru release).
2. Download and install [this magisk module](https://github.com/gloeyisk/universal-gms-doze/releases).
3. Reboot phone
4. Download [this apk](https://github.com/whew-inc/FakeGApps/releases).
5. copy that apk onto your phone and install it.
6. and when done click done and click the notification from LSPosed to enable it.
7. Reboot phone.
8. Now to install MicroG, but as a system app, so we start with version 0.3.4 downloading and installing these apks [microG Services 0.3.4.240913](https://www.apkmirror.com/apk/microg-team/microg-services-core/microg-services-core-0-3-4-240913-release/microg-services-0-3-4-240913-android-apk-download/), [microG Companion 0.3.4.40226 (Android 4.4+)/](https://www.apkmirror.com/apk/microg-team/fakestore/fakestore-0-3-4-40226-release/microg-companion-0-3-4-40226-android-apk-download/).
9. Now you need [microG Installer Revived](https://github.com/nift4/microg_installer_revived/releases) to systemize them, we used 0.3.4 because it is compatible with this module. It will also install MicroG Framework Proxy.
10. Reboot Phone.
11. Install this Magisk module [Android Auto 4 MicroG](https://github.com/sn-00-x/aa4mg/releases) Select no for Gapps Stub.Select no for Gapps Stub and if you installed the TTS Module select no for the TTS stub
12. Reboot and install [Maps.apk](https://github.com/sn-00-x/aa4mg/blob/master/system/product/app/Maps/Maps.apk).
13. download and install [F-Droid Basic apk](https://f-droid.org/en/packages/org.fdroid.basic/).
14. go into F-Droid basic settings>repositories> and add [this mocroG F-droid repository](https://microg.org/fdroid/repo/?fingerprint=9BD06727E62796C0130EB6DAB39B73157451582CBD138E86C468ACC395D14165)
15. Update the microG apps and services within F-Droid Basic.
# Best Cat S22 Keypad 
[TT9](https://f-droid.org/en/packages/io.github.sspanak.tt9/)
# Video Games for keypad and small screen
Before smartphones, developers would make video games for flip phones  with keypads in the Java Programming language.
[The JL-Mod App](https://github.com/woesss/JL-Mod) and [the J2ME Loader app](https://github.com/nikita36078/J2ME-Loader) allow you to run those old games on your flip phone.
[This](https://mobile.phoneky.com/games/?q=nokia) is a website that lets you download those old java games as '.jar' files and copy them onto your flip phone which you can then install with either the JL-mod app or the J2ME loader app.
# Keymapping
1. Download [V2.8.3](https://github.com/keymapperorg/KeyMapper/releases/tag/v2.8.3) of the key mapper onto your phone and go through the key mapper setup.
2. Go to the keymapper settings within the keymapper app and enable root access for keymapper.
3. Download [this zip file](https://github.com/rozeraize/CatS22FlipGuide-Tips/blob/main/keymaps/mappings_20260429-161013.zip) onto your phone. 
4. In the keymapper app open the side panel click the 'restore' button'. Navigate to the folder that you saved the zip file to and click on the zip file.
5. Now if you double-press the speaker button it opens the app menu in whatever app your in.
6. Now go and make whatever keymaps you want (Note: if you wanna map the orange button on the side of the phone go to 'Settings>Programmable Key>' and enable PTT Mode.)
# Apps
1. Podcast App: [PodLP](https://www.podlp.com/)
2. Music Player: [D-PAD Player](https://github.com/jbriones95/D-PAD-Player)
# Forums and resources for flip phone apps
1. [Here](https://forums.jtechforums.org/t/uploaded-apps-thread/) is a forum thread for apps that will work for flip phones.
2. [Here](https://forums.apps4flip.com/d/53-uploaded-apps) is anather forum thread for apps that will work for flip phones.
3. [Here](https://jtechforums.org/apps) is yet another website with apps modified for flip phones, and it has a great forum with lots of other tips and apps and hacks for many flip phones including the Cat S22 flip.




