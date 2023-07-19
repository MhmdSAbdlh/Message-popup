# java-swing-confirm-message
Date : 11/03/2022<br/>
How to coding in java
visit my youtube : https://www.youtube.com/c/HelloWorld-Raven/featured
<br/><br/>
CODING:

UPDATE MESSAGE:

UpdateMessage obj = new UpdateMessage(JFrame);

obj.showMessage("TITLE","changeLog");

if (obj.getMessageType() == MessageDialog.MessageType.OK)
 
if (obj.getMessageType() == MessageDialog.MessageType.CANCEL)


<br/><br/>
SOCIAL MEDIA MESSAGE:

SocialMedia socialMedia = new SocialMedia(JFrame);

socialMedia.setLinks("https://www.youtube.com/", "https://website.com/",
					"https://www.facebook.com/", "https://xxx.github.io/",
					"https://www.instagram.com/", "https://twitter.com/");
			
socialMedia.showMessage("message");
<br/><br/>
<br/><br/>
MESSAGE DIALOG:

MessageDialog obj = new MessageDialog(JFrame);

obj.showMessage("MESSAGE");

if (obj.getMessageType() == MessageDialog.MessageType.OK)

    
if (obj.getMessageType() == MessageDialog.MessageType.CANCEL)

<br/><br/>
OPTION DIALOG:

OptionDialog op1 = new OptionDialog(JFrame);

op1.showMessage("message", "sub message"); // you can use a countdown for the try left

if (obj.getMessageType() == MessageDialog.MessageType.OK)


if (obj.getMessageType() == MessageDialog.MessageType.CANCEL)

<br/><br/>    
PHOTOS:
![2022-03-10_230130](https://user-images.githubusercontent.com/58245926/157719453-9c3fba27-4871-48b1-b695-cbbe443686c0.png)
![(https://github.com/MhmdSAbdlh/Message-popup/blob/main/05.png)](https://raw.githubusercontent.com/MhmdSAbdlh/Message-popup/main/05.png)
![PHTO2](https://raw.githubusercontent.com/MhmdSAbdlh/Message-popup/main/ABOUT.png)
![UPDATE](https://raw.githubusercontent.com/MhmdSAbdlh/Message-popup/main/UPDATE.png)
