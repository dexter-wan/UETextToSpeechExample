### [中文文档](https://dt.cq.cn/archives/1008?from=github)

This plug-in can use blueprints in UE to convert text into speech playback. The sound engine used for playback uses the Windows built-in speech engine and supports Win10 and Win11.

# System Settings

First, confirm whether the computer has a voice system. Generally, a normally installed computer will have one built-in.

![System Settings](https://dt.cq.cn/wp-content/uploads/2024/06/image-17.png)

If you want to play in multiple languages, please download the voice library in other languages ​​yourself. Generally, the system only comes with English and the system default language.

![System Settings](https://dt.cq.cn/wp-content/uploads/2024/06/image-18.png)

# Blueprint Operations

![Blueprint Operations](https://dt.cq.cn/wp-content/uploads/2024/06/image-5.png)

First, add a DT Speech Voice Component in the Actor.

Then the created component object is the operation object, which can be used for playback operations.

![](https://dt.cq.cn/wp-content/uploads/2024/06/image-6.png)

# Node Description

## Speak
![Speak](https://dt.cq.cn/wp-content/uploads/2024/06/image-8.png)

Play voice

Speak Content: The content to be played.

## Set Volume
![Set Volume](https://dt.cq.cn/wp-content/uploads/2024/06/image-10.png)

Set playback volume: 0 – 100

## Set Rate
![Set Rate](https://dt.cq.cn/wp-content/uploads/2024/06/image-11.png)

Set playback rate: -10 – 10

## Pause
![Pause](https://dt.cq.cn/wp-content/uploads/2024/06/image-12.png)

Pause audio playback

## Resume
![Resume](https://dt.cq.cn/wp-content/uploads/2024/06/image-13.png)

Resume voice playback

## Stop
![Stop](https://dt.cq.cn/wp-content/uploads/2024/06/image-14.png)

Stop voice playback and cannot be resumed

## Get Tokens
![Get Tokens](https://dt.cq.cn/wp-content/uploads/2024/06/image-15.png)

Get the current system valid voice type

## Set Token
![Set Token](https://dt.cq.cn/wp-content/uploads/2024/06/image-16.png)

Set the type of voice currently being played

# Download link

### [Text To Speech in Code Plugins – UE Marketplace](https://www.unrealengine.com/marketplace/en-US/product/2e2d62162d8e4c518df5d0fb6b83a6fd)
