# feishu-dark-mode

飞书网页版深色模式（黑夜、夜晚），使用 Google Chrome App 可在 macOS Dock 中直接启动。

*WORK IN PROGRESS*

Patched:

<img src="https://user-images.githubusercontent.com/1284703/145839196-9e272638-d613-4bbe-ac9d-59ce561ce59a.png" width="100%">

Original:

<img src="https://user-images.githubusercontent.com/1284703/145839702-8f5dd9e6-5d8c-4949-940b-050073e9ddb0.png" width="100%">

## Usage

1. Install Stylebot Extension in Google Chrome.
2. Copy CSS code in feishu.css to Stylebot.

## Create a Google Chrome App

1. Open https://feishu.cn/messenger/ in Google Chrome
2. Menu > More Tools > Create Shortcut
<img src="https://user-images.githubusercontent.com/1284703/145839174-edf3d463-c864-4b01-ae2d-9c4b0d416c90.png" width="500">
3. Change Name and Check "Open as window"
<img src="https://user-images.githubusercontent.com/1284703/145839184-c4877c76-b8b9-451d-8c14-6189c89a598e.png" width="500">
4. Click Get Info on the app
<img src="https://user-images.githubusercontent.com/1284703/145839189-7611cf3c-0f6e-4fcd-982e-ef7354b3c8f4.png" width="500">
5. Drag the icns file to the Get Info window to update the icon.
<img src="https://user-images.githubusercontent.com/1284703/145839193-acab2d98-a1a9-43b6-bda3-23221dec3598.png" width="500">

## Make .icns file

You can use .icns file in this repository or generate one by yourself. Needs macOS system.

1. Download `feishu.png` and the `make-icns` script file and put them in the same folder.
2. Open Terminal and type `bash ` (b-a-s-h-space), and then drag the make-icns file to the Terminal window.
3. Press Enter key to execute the script.
4. You will see Feishu.icns file in that folder.
