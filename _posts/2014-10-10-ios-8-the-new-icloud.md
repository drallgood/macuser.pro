---
ID: 49
post_title: 'iOS 8: The New iCloud'
author: "Patrice Brend'amour"
post_date: 2014-10-10 22:02:27
post_excerpt: "<p>iCloud has been at the center of Apple's ecosystem for a couple of years now. It's very versatile and can serve as a handy storage solution for your photos and documents, as a sync service for contacts and calendars or as a database backend for your apps.</p><p>With the release of iOS 8 and OS X Yosemite, this is about to change. Back in June, Apple announced a new feature called iCloud drive that will replace the more limited iCloud we all know with a more open, Dropbox-like version of itself. iCloud Drive not only acts as a real drive on OS X, it also allows selective access to the same set of files for multiple apps (more on that later) on iOS.</p>"
layout: post
permalink: >
  http://macuser.pro/2014/10/10/ios-8-the-new-icloud/
published: true
ac_featured_article:
  - "1"
ac_show_post_thumbnail:
  - ""
video_url:
  - ""
audio_url:
  - ""
quote_content:
  - ""
quote_attribution:
  - ""
link_url:
  - ""
link_title:
  - ""
---




iCloud has been at the center of Apple's ecosystem for a couple of years now. It's very versatile and can serve as a handy storage solution for your photos and documents, as a sync service for contacts and calendars or as a database backend for your apps. Initially deemed unreliable, partially due to its abysmal predecessors but also because it clearly needed some work, it has evolved into the ever present, reliable service we enjoy today. 

However, there were a few limitations:  
For one, documents couldn't be shared between apps. Each app had its own "iCloud container", which contained only the documents this particular app had created. No other app could access those documents. If you wanted to open the same file in a different app, or use an intricate multi-app workflow, you had to copy the file to that app (or multiple apps) which resulted in multiple copies of the same file. This is surely one of the reasons why most writers and developers have shied away from using iCloud for their workflows and have used services like Dropbox instead. 

Further, there was no way of storing arbitrary files (e.g. from apps that aren't even in the app store) in iCloud. There was no special folder (like Dropbox has) where you could just store a file and access it on another device.

With the release of iOS 8 and OS X Yosemite, this is about to change. Back in June, Apple announced a new feature called iCloud drive that will replace the more limited iCloud we all know with a more open, Dropbox-like version of itself. iCloud Drive not only acts as a real drive on OS X, it also allows selective access to the same set of files for multiple apps (more on that later) on iOS. Now you can take a picture using Fast Camera, edit it with Waterlogue and then post it on Flicker, without creating multiple copies of the same file.

![iCloud Drive document picker][iclouddoc]

Apple also changed the pricing structure of iCloud, making it not only way cheaper than it was before, but also adding storage tiers of up to 1TB.

![New iCloud pricing][icloudpricing]

You still get the same 5GB for free, if you need more than that, you have the following choices:

- $0.99/month for 20GB
- $3.99/month for 200GB
- $9.99/month for 500GB
- $19.99/month for 1TB

## Migration

![icloud drive migration screen][iCloudDriveMigration]

When upgrading your iOS devices to iOS8, it will prompt you to upgrade to iCloud drive. This is due to the fact that iCloud drive is not compatible with the old version of iCloud. Upon upgrading to iCloud drive, you loose the capability to sync with devices that run iOS 7 or OS X Mavericks (and earlier), so make sure you're upgrading all your devices at once.  If you don't want to do it just yet, just skip this step. You'll be able to upgrade at a later point in time.

Once you've migrated to iCloud drive, it will just start working. No need to do anything. You won't even notice any significant differences on iOS (You will on OS X, but that one isn't released yet. We'll have another article out in time for its relase that will detail some of the changes). 

## How it works
Even with iCloud drive, every document is stored in the iCloud container of the app that created it. So, for example, if you create a new document in Pages, it will be stored in Pages' iCloud container. No other app can access it unless you've authorized it. But how does that work? 

Every time you try to open a file in one of the myriad of iCloud enabled apps, a iCloud drive view will open up and allow you to select the file(s) you want to work on. Once you've selected your files, the app will be granted access to those files and only those. Other files in the same container won't be available to the app. Please keep in mind, that you're editing the original file, not a copy of it. Whatever changes you make to it, will be available to other apps, too.

## Upgrading your storage plan <a name="upgrade-storage"></a>

Especially for businesses, online storage like iCloud and Dropbox is an essential tool for storing, syncing and organizing your files. It enables you to access your files wherever you are and on whatever device you're using. Rarely will iCloud's free storage tier (5GB) be enough to store all your business's files. So, how do you upgrade your storage plan?

If you're an existing subscriber of iCloud, Apple has already sent you an email notifying you about the upgraded plans and prices. They've also informed you about your new, upgraded storage plan. The good news is, that you likely won't have to do anything. Your account has been upgraded and chances are, whatever tier of storage you're paying for right now will be enough for your needs (it has been in the past, so why wouldn't it?).

Whether you're an existing subscriber or you're using the free tier, there's an easy way to upgrade to a higher storage plan. Just open up the ```Settings``` app on your iPad or iPhone and scroll down to the iCloud settings. 

![iCloud settings][icloudSettings]

Once you've opened those, tap on ```Storage``` and select ```Change Storage Plan``` (it might also be called ```Buy More Storage```) on the next screen.

![iCloud Storage settings][icloudSettings2]

![iCloud Storage Plan][icloudSettings3]

 Now you should see your current plan and also the mentioned upgrade options and prices. Just select one, sign in with your Apple ID and you're done. You've successfully "expanded" your iCloud drive to your new storage size.

Of course you can downgrade to a lower tier at any point in time. Just keep in mind, that this will shrink your drive.

[iclouddoc]: /wp-content/uploads/2014/10/icloud_drive.png "iCloud Drive document picker"
[icloudpricing]: /wp-content/uploads/2014/10/img1.png "New iCloud pricing"
[icloudSettings]: /wp-content/uploads/2014/10/icloud_settings.png "iCloud setting item in Settings app"
[icloudSettings2]: /wp-content/uploads/2014/10/icloud_settings2.png "Storage option"
[icloudSettings3]: /wp-content/uploads/2014/10/icloud_settings3.png "Buy more Storage"
[iCloudDriveMigration]: /wp-content/uploads/2014/10/icloud_drive_migration.png "iCloud Drive migration"