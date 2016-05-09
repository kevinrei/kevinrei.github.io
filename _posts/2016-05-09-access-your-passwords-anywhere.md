---
layout: post
title: "Access Your Passwords Anywhere with KeePass and Dropbox"
date: 2016-05-09
excerpt: "KeePass and Dropbox together are a force to be reckoned with."
tags: [blog, tech, tutorial]
comments: true
---

<center><b><i>Originally posted on 1/30/2016 on WordPress.  Moved and edited on 5/9/2016.</i></b></center>

<br>

## Quick Navigation
1. [Sign Up on Dropbox](#section-1)
2. [Download and Install Dropbox](#section-2)
3. [Download and Install KeePass](#section-3)
4. [Open KeePass and Create a New .kdbx File](#section-4)
5. [Link Your Dropbox File to KeePass](#section-5)
6. [KeePass with Other Tools](#section-6)
    1. [KeePass with Android](#section-6-1)
    2. [KeePass with iOS](#section-6-2)
    3. [KeePass with Google Chrome](#section-6-3)
	
<br>

I have so many passwords online that I can never keep track of them.  I dislike using the same passwords for things because of security reasons as well.  That's why I rely on <a href="http://keepass.info/" target="_blank">KeePass</a>, just so I can just look up the password for a specific site or service and I'm good to go.  The perks of it include the fact that it's completely **free** and **open-source**.  If you have concerns about how safe this software actually is, you can verify it yourself by diving into the encryption algorithms.

But I'm *lazy*.  I don't want to turn on my PC or carry it around just to access KeePass and get passwords for my mobile device.  And what if I'm outdoors?  There's no way I can get to my password.  I'd have to *remember*.  I don't want that, so I'll just download the KeePass app and copy over my .kdbx file to that device.  No problem.

But like I said, I'm **_lazy_**.  I don't want to keep copying over the up-to-date .kdbx file every time I change my it on desktop or vice versa.  That's just too much work.  So I access my .kdbx from a data management service like <a href="https://www.dropbox.com/" target="_blank">Dropbox</a>.  With Dropbox, you can virtually access your files through any device (including browser access, so yes, any computer as well), create public folders to drop files you'd like to share (resumes, etc.), and share files and links with collaborators, family members, anyone.

So whenever I update the .kdbx file in my Dropbox folder, regardless of what device I'm on, it'll always be synced.  Just remember that:

* You must have some form of KeePass client on the device (desktop, mobile, or browser).
* Your .kdbx file must be in your Dropbox folder.
* You **must** remember your KeePass master password.  

Set up is super easy.

----------

<div id='section-1'/>
## 1. Sign Up on Dropbox

<center><figure>
	<a href="https://cloud.githubusercontent.com/assets/8562283/15129078/038e2aa0-1605-11e6-8128-d2dac1459586.png"><img src="https://cloud.githubusercontent.com/assets/8562283/15129078/038e2aa0-1605-11e6-8128-d2dac1459586.png"></a>
	<figcaption>The first step is to create an account on Dropbox, if you don't have one yet.</figcaption>
</figure></center>

First thing's first: sign up on Dropbox through their <a href="https://www.dropbox.com/" target="_blank">website</a>, if you don't have an account.  It'd be nice if you can use my <a href="https://db.tt/CaNF7onK" target="_blank">referral</a>, but it's not necessary.  Just a note: you can link your account to social media later if you'd like to collaborate, earn more storage space, etc.

&nbsp;

<div id='section-2'/>
## 2. Download and Install Dropbox

<center><figure>
	<a href="https://cloud.githubusercontent.com/assets/8562283/15129077/038939b4-1605-11e6-9d24-e169ef110830.png"><img src="https://cloud.githubusercontent.com/assets/8562283/15129077/038939b4-1605-11e6-9d24-e169ef110830.png"></a>
	<figcaption>You should see your Dropbox folder in File Explorer after you successfully install it.</figcaption>
</figure></center>

After creating a new account or following the download link, you should install it.  After successful installation, your Dropbox folder should be located in your File Explorer.  Now you have Dropbox on your computer!  Add stuff here, and you can access them from any browser or Dropbox-enabled devices.

&nbsp;

<div id='section-3'/>
## 3. Download and Install KeePass

<center><figure>
	<a href="https://cloud.githubusercontent.com/assets/8562283/15129082/03939134-1605-11e6-836c-5b6384e35624.png"><img src="https://cloud.githubusercontent.com/assets/8562283/15129082/03939134-1605-11e6-836c-5b6384e35624.png"></a>
	<figcaption>Go to the latest release and follow the download link.</figcaption>
</figure></center>

Now it's time to get KeePass.  You can get it directly from their <a href="http://keepass.info/" target="_blank">website</a>.  As indicated in the image, make sure you get the latest version (KeePass 2.31 as of 1/30/2016) so you have the most up-to-date features.  Make sure it's a stable release.

&nbsp;

<div id='section-4'/>
## 4. Open KeePass and Create a New .kdbx File

<center><figure>
	<a href="https://cloud.githubusercontent.com/assets/8562283/15129084/039c57e2-1605-11e6-8ad1-d0e915bee24b.png"><img src="https://cloud.githubusercontent.com/assets/8562283/15129084/039c57e2-1605-11e6-8ad1-d0e915bee24b.png"></a>
	<figcaption>Make sure your new database is saved into the Dropbox folder that was made after installation.</figcaption>
</figure></center>

Navigate to File > New, and save your new .kdbx file into the Dropbox folder that was created.  Make sure you save it in the correct path, or the synchronization won't work.

<br>

<center><figure>
	<a href="https://cloud.githubusercontent.com/assets/8562283/15129081/038f9bb0-1605-11e6-8851-2a14ba495ac3.png"><img src="https://cloud.githubusercontent.com/assets/8562283/15129081/038f9bb0-1605-11e6-8851-2a14ba495ac3.png"></a>
	<figcaption>Create a strong, unforgettable master password.</figcaption>
</figure></center>

Once you save your new file, you will get to this page.  Type in a strong master password and don't forget it!  Please don't use a really basic password (like 123456, which was 2015's most common password).  If you need some inspiration, you can refer to <a href="http://windows.microsoft.com/en-us/windows-vista/tips-for-creating-a-strong-password" target="_blank">Microsoft's tips</a>, <a href="http://lmgtfy.com/?q=how+to+create+a+strong+password" target="_blank">your best friend Google</a>, or use a password generator.  <a href="http://keepass.info/help/base/pwgenerator.html" target="_blank">KeePass also has a built-in password generator</a>

&nbsp;

<div id='section-5'/>
## 5. Link Your File on Dropbox to KeePass

<center><figure>
	<a href="https://cloud.githubusercontent.com/assets/8562283/15129079/038e5d22-1605-11e6-9bac-e730df4b4cbc.png"><img src="https://cloud.githubusercontent.com/assets/8562283/15129079/038e5d22-1605-11e6-9bac-e730df4b4cbc.png"></a>
	<figcaption>The key file is the one you saved in your Dropbox folder.</figcaption>
</figure></center>

Navigate to the file you saved on your Dropbox and open it.  You will be able to link your .kdbx file with your KeePass, and you can verify that with the file path.  Now, all you need to do is type in your master password!  Congratulations, you now have KeePass accessible on your desktop and it'll always be up-to-date!

&nbsp;

<div id='section-6'/>
## 6. KeePass with Other Tools

<div id='section-6-1'/>
### 6.1: KeePass with Android

If you have an Android device, I recommend getting <a href="https://play.google.com/store/apps/details?id=keepass2android.keepass2android&amp;hl=en" target="_blank">Keepass2Android on Google Play</a>.

<center><figure>
	<a href="https://cloud.githubusercontent.com/assets/8562283/15129080/038e7834-1605-11e6-8cf7-3816522e8443.png"><img src="https://cloud.githubusercontent.com/assets/8562283/15129080/038e7834-1605-11e6-8cf7-3816522e8443.png"></a>
	<figcaption>Open your .kdbx file in Keepass2Android.</figcaption>
</figure></center>

In Keepass2Android, you can either open an existing file or create a new database.  Of course, you'd want to open the .kdbx file in your Dropbox!  Go to Open file > Dropbox, and navigate to the file.  After that, type in your master password, and you're in!  Naturally, you can create, edit, and delete passwords and it will be synchronized.

&nbsp;

<div id='section-6-2'/>
### 6.2: KeePass with iOS

If you have an iOS device, I recommend getting <a href="https://itunes.apple.com/us/app/minikeepass-secure-password/id451661808?mt=8" target="_blank">MiniKeePass from the iOS App Store</a>.

If you went right into the MiniKeePass app after installation, you might be confused.  The + button only adds a new KeePass file!  No problem, you can still get your .kdbx file.

<center><figure>
	<a href="https://cloud.githubusercontent.com/assets/8562283/15129083/0393fbce-1605-11e6-89b8-c6b2af885bc8.png"><img src="https://cloud.githubusercontent.com/assets/8562283/15129083/0393fbce-1605-11e6-89b8-c6b2af885bc8.png"></a>
	<figcaption>In your Dropbox app on iOS, copy the .kdbx file to MiniKeePass.</figcaption>
</figure></center>

Open your Dropbox app on your Apple device.  Navigate to your .kdbx file, and click the upload (box-with-arrow) icon.  Click Open In > Copy to MiniKeePass.  Go back to MiniKeePass, and your file should be listed.  Type in your master password, and you're now you're in!  All updates from this app will be synchronized.

&nbsp;

<div id='section-6-3'/>
### 6.3: KeePass with Google Chrome

There is a Google Chrome extension for KeePass called <a href="https://chrome.google.com/webstore/detail/ckp-keepass-integration-f/lnfepbjehgokldcaljagbmchhnaaogpc" target="_blank">CKP</a>.  This is a **read-only** extension that will quickly access your database and display the related entry.

<center><figure>
	<a href="https://cloud.githubusercontent.com/assets/8562283/15129086/039cc2cc-1605-11e6-9462-029dd0cdd5db.png"><img src="https://cloud.githubusercontent.com/assets/8562283/15129086/039cc2cc-1605-11e6-9462-029dd0cdd5db.png"></a>
	<figcaption>CKP helps you look up your database with ease. Autofill is an option, but not necessary.</figcaption>
</figure></center>

After adding the extension, you will see the CKP icon in the address bar (for websites that are relevant).  Go to the settings page by clicking the link.

<center><figure>
	<a href="https://cloud.githubusercontent.com/assets/8562283/15129085/039c72c2-1605-11e6-9ffa-827f9695ac25.png"><img src="https://cloud.githubusercontent.com/assets/8562283/15129085/039c72c2-1605-11e6-9ffa-827f9695ac25.png"></a>
	<figcaption>CKP thankfully has Dropbox integration.</figcaption>
</figure></center>

Navigate to the KeePass Databases tab, and there should be a Dropbox icon.  Click on it, and log into Dropbox as instructed.

<center><figure>
	<a href="https://cloud.githubusercontent.com/assets/8562283/15129088/03a083bc-1605-11e6-8b59-514607724b7e.png"><img src="https://cloud.githubusercontent.com/assets/8562283/15129088/03a083bc-1605-11e6-8b59-514607724b7e.png"></a>
	<figcaption>The verification is a bit confusing, but if you see something similar to this, you're good.</figcaption>
</figure></center>

Once you add the file, you're set.  At first, clicking the .kdbx does nothing so it may worry you, but it should be working.

<center><figure>
	<a href="https://cloud.githubusercontent.com/assets/8562283/15129076/037c4272-1605-11e6-9637-8e375a26e547.png"><img src="https://cloud.githubusercontent.com/assets/8562283/15129076/037c4272-1605-11e6-9637-8e375a26e547.png"></a>
	<figcaption>CKP finds the relevant entries. You can also find the desired entry manually.</figcaption>
</figure></center>

Now, whenever you go on relevant websites and click on the CKP icon, you can type in your master password and check the entry for that website.  Remember, this is read-only.  If you want to add a new entry, you must use a different method.

----------

And that's basically it!  You're now able to access all of your passwords anywhere.  Having many passwords might be more secure than overusing one, and having a password manager that's accessible anywhere is such a useful tool.  I hope this Dropbox-KeePass interaction helps you as much as it helps me everyday!