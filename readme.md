# Paircast Video

This repository was created with [Paircast](https://app.paircast.io/replay/f2ace53b-b035-4d95-9f04-2bec2eabd414).

<a href="https://app.paircast.io/replay/f2ace53b-b035-4d95-9f04-2bec2eabd414"><img src="https://app.paircast.io/replay/f2ace53b-b035-4d95-9f04-2bec2eabd414/screenshot" alt="Screenshot of Paircast Recording" width="400" /></a> 

<a href="https://app.paircast.io/replay/f2ace53b-b035-4d95-9f04-2bec2eabd414"><img src="https://app.paircast.io/images/watch-on-paircast.png" alt="Watch on Paircast" /></a> 

[Watch on Paircast](https://app.paircast.io/replay/f2ace53b-b035-4d95-9f04-2bec2eabd414) to see this project built line-by-line.

Paircast records file changes, desktop video, camera, microphone, and open applications as you code.

----

Now it's time to make th readme. Read me That kind of says Oh, hey, you know if there's no, really it says, Hey, this is made with pear cast some thing it did. Was it get branched? So now we're on a branch of the future location of this pair cast recording. I could get into that later. <sup><a href="https://app.paircast.io/c/t78vtYge5/1350">00:01</a></sup>

`Code.exe > readme.md - electron-notify - Visual Studio Code` <sup><a href="https://app.paircast.io/c/t78vtYge5/10140">00:10</a></sup>
A
But so we're not gonna be overriding any work in master's going on ly be working in that guest branch. <sup><a href="https://app.paircast.io/c/t78vtYge5/20160">00:20</a></sup>

And you'll notice here that we're watching for changes in electron Notify. So, for example, if I let just say I make a new file here. <sup><a href="https://app.paircast.io/c/t78vtYge5/28000">00:28</a></sup>

And we'll call it `main.js`, which I think this is what Victoria wants. <sup><a href="https://app.paircast.io/c/t78vtYge5/36410">00:36</a></sup>

`Code.exe > readme.md - electron-notify - Visual Studio Code` <sup><a href="https://app.paircast.io/c/t78vtYge5/40140">00:40</a></sup>

Um and I just heave our Abel's be say that hair cast has noticed that file and you'll notice that it also gave you a confirmation. It's tracking, so things are working. <sup><a href="https://app.paircast.io/c/t78vtYge5/41700">00:41</a></sup>

I think we actually want this to be my main JSF. Things were working out and we're going to continue with our tutorial. We know it works. We know it's tracking, and we can keep looking at sarcastic and firm. As we go. You'll also notice there's a max length here that's determined by your plan. <sup><a href="https://app.paircast.io/c/t78vtYge5/57130">00:57</a></sup>

<sup><a href="https://app.paircast.io/c/t78vtYge5/71350">01:11</a></sup>

<a href="https://app.paircast.io/c/t78vtYge5/71350"><img src="https://app.paircast.io/replay/f2ace53b-b035-4d95-9f04-2bec2eabd414/screenshot?timestamp=71350&shareKey=yw6BsOjDjCgcqNEDjlUTg" width="300" alt="Paircast Screenshot at Minute 1" /></a>

And any plan you get two hours. The free trial is currently half an hour. <sup><a href="https://app.paircast.io/c/t78vtYge5/71350">01:11</a></sup>

So for our tutorial here, we're going to copy and paste from the electron docks. If you're doing it tutorial yourself. You're probably be a little bit more hands on a little more talkative, probably explaining things a lot more. Here we go again. We're talking about here cast, so let's just copy and paste that <sup><a href="https://app.paircast.io/c/t78vtYge5/77470">01:17</a></sup>

`chrome.exe > Quick Start Guide | Electron - Google Chrome` <sup><a href="https://app.paircast.io/c/t78vtYge5/80144">01:20</a></sup>

<sup><a href="https://app.paircast.io/c/t78vtYge5/92038">01:32</a></sup>

```diff
Commit 6bcac6bd0aa0c19a4adae2e376b448c54a8ef704
--- main.js
+++ main.js
@@ -1 +1,28 @@
-var a = b;
+const { app, BrowserWindow } = require('electron')
+
+function createWindow() {
+    const win = new BrowserWindow({
+        width: 800,
+        height: 600,
+        webPreferences: {
+            nodeIntegration: true
+        }
+    })
+
+    win.loadFile('index.html')
+    win.webContents.openDevTools()
+}
+
+app.whenReady().then(createWindow)
+
+app.on('window-all-closed', () => {
+    if (process.platform !== 'darwin') {
+        app.quit()
+    }
+})
+
+app.on('activate', () => {
+    if (BrowserWindow.getAllWindows().length === 0) {
+        createWindow()
+    }
+})

```

We'll see again. Pair cast has detected that change. One deletion 20th edition, So it's working greats. <sup><a href="https://app.paircast.io/c/t78vtYge5/93440">01:33</a></sup>

On our way. <sup><a href="https://app.paircast.io/c/t78vtYge5/99880">01:39</a></sup>

`chrome.exe > Quick Start Guide | Electron - Google Chrome` <sup><a href="https://app.paircast.io/c/t78vtYge5/100146">01:40</a></sup>

Tutorial here tells us to make an index dot html. So let's make a new file. <sup><a href="https://app.paircast.io/c/t78vtYge5/102190">01:42</a></sup>

We'll call that index dot html boom again. Parka sees it. Um, I know already. This needs tohave him. Ah, you know, I'll show that on screen. We also need a package. Jason. So let's take this package. Jason here. <sup><a href="https://app.paircast.io/c/t78vtYge5/106670">01:46</a></sup>

`Code.exe > ● index.html - electron-notify - Visual Studio Code` <sup><a href="https://app.paircast.io/c/t78vtYge5/110149">01:50</a></sup>

<sup><a href="https://app.paircast.io/c/t78vtYge5/120152">02:00</a></sup>

<a href="https://app.paircast.io/c/t78vtYge5/120152"><img src="https://app.paircast.io/replay/f2ace53b-b035-4d95-9f04-2bec2eabd414/screenshot?timestamp=120152&shareKey=yw6BsOjDjCgcqNEDjlUTg" width="300" alt="Paircast Screenshot at Minute 2" /></a>

`chrome.exe > Quick Start Guide | Electron - Google Chrome` <sup><a href="https://app.paircast.io/c/t78vtYge5/120152">02:00</a></sup>

We'll open up the one that we've got, and we will put it there. Great. So packet Jason's been modified and we should be able to now go into terminal and run A P. M start. <sup><a href="https://app.paircast.io/c/t78vtYge5/123300">02:03</a></sup>

<sup><a href="https://app.paircast.io/c/t78vtYge5/125741">02:05</a></sup>

```diff
Commit 2ef4c173670c6b3f371d93c96413f24ae4e38428
--- package.json
+++ package.json
@@ -1,15 +1,8 @@
 {
-  "name": "electron-notify",
-  "version": "1.0.0",
-  "description": "",
-  "main": "index.js",
+  "name": "my-electron-app",
+  "version": "0.1.0",
+  "main": "main.js",
   "scripts": {
-    "test": "echo \"Error: no test specified\" && exit 1"
-  },
-  "keywords": [],
-  "author": "",
-  "license": "ISC",
-  "devDependencies": {
-    "electron": "^10.1.5"
+    "start": "electron ."
   }
 }

```

`Paircast.exe > Paircast` <sup><a href="https://app.paircast.io/c/t78vtYge5/130158">02:10</a></sup>

Boom. Okay, so that gives us our Hello, World electron tutorial. <sup><a href="https://app.paircast.io/c/t78vtYge5/135920">02:15</a></sup>

`ConEmu64.exe > Cmder` <sup><a href="https://app.paircast.io/c/t78vtYge5/140157">02:20</a></sup>

And what we're going to do now is modified a little bit, so if we just simply add a style tag. <sup><a href="https://app.paircast.io/c/t78vtYge5/140170">02:20</a></sup>

`Code.exe > ● index.html - electron-notify - Visual Studio Code` <sup><a href="https://app.paircast.io/c/t78vtYge5/150157">02:30</a></sup>

Text Yes. <sup><a href="https://app.paircast.io/c/t78vtYge5/150340">02:30</a></sup>

How'd we do? <sup><a href="https://app.paircast.io/c/t78vtYge5/153000">02:33</a></sup>

Back ground color whites <sup><a href="https://app.paircast.io/c/t78vtYge5/154410">02:34</a></sup>

<sup><a href="https://app.paircast.io/c/t78vtYge5/157192">02:37</a></sup>

```diff
Commit 05edbcd27e25e4c5c94e924f482a4c4b6f1b19c5
--- index.html
+++ index.html
@@ -5,6 +5,9 @@
     <meta charset="UTF-8">
     <title>Hello World!</title>
     <meta http-equiv="Content-Security-Policy" content="script-src 'self' 'unsafe-inline';" />
+    <style type="text/css">
+        background-color: white;
+    </style>
 </head>
 
 <body>

```

I always forget to write body here. Okay, There we go. Save it. So I made a mistake there and that'll show up in the transcript. I'll show you later How we can edit out a mistake like that. But here we can see its detected all those changes. You know, again. We're still logging. What's going on? <sup><a href="https://app.paircast.io/c/t78vtYge5/158350">02:38</a></sup>

<sup><a href="https://app.paircast.io/c/t78vtYge5/162074">02:42</a></sup>

```diff
Commit 7190655488ad4e3764c5839ec2c0fe739602bcfb
--- index.html
+++ index.html
@@ -6,7 +6,10 @@
     <title>Hello World!</title>
     <meta http-equiv="Content-Security-Policy" content="script-src 'self' 'unsafe-inline';" />
     <style type="text/css">
-        background-color: white;
+        body {
+            background-color: white;
+
+        }
     </style>
 </head>
 

```

<sup><a href="https://app.paircast.io/c/t78vtYge5/163133">02:43</a></sup>

```diff
Commit cb363786cce500701d210c808f41bec7c6a60788
--- index.html
+++ index.html
@@ -1,26 +0,0 @@
-<!DOCTYPE html>
-<html>
-
-<head>
-    <meta charset="UTF-8">
-    <title>Hello World!</title>
-    <meta http-equiv="Content-Security-Policy" content="script-src 'self' 'unsafe-inline';" />
-    <style type="text/css">
-        body {
-            background-color: white;
-
-        }
-    </style>
-</head>
-
-<body>
-    <h1>Hello World!</h1>
-    We are using node
-    <script>document.write(process.versions.node)</script>,
-    Chrome
-    <script>document.write(process.versions.chrome)</script>,
-    and Electron
-    <script>document.write(process.versions.electron)</script>.
-</body>
-
-</html>

```

`Paircast.exe > Paircast` <sup><a href="https://app.paircast.io/c/t78vtYge5/170161">02:50</a></sup>

Um, so we've modified that file over three minutes in. If we start the APP to get the white background that's great. <sup><a href="https://app.paircast.io/c/t78vtYge5/174580">02:54</a></sup>

<sup><a href="https://app.paircast.io/c/t78vtYge5/180164">03:00</a></sup>

<a href="https://app.paircast.io/c/t78vtYge5/180164"><img src="https://app.paircast.io/replay/f2ace53b-b035-4d95-9f04-2bec2eabd414/screenshot?timestamp=180164&shareKey=yw6BsOjDjCgcqNEDjlUTg" width="300" alt="Paircast Screenshot at Minute 3" /></a>

`ConEmu64.exe > Cmder` <sup><a href="https://app.paircast.io/c/t78vtYge5/180164">03:00</a></sup>

So we're going to do now is work with electron notifications. <sup><a href="https://app.paircast.io/c/t78vtYge5/185060">03:05</a></sup>

It isthe notifications notifications on vacation there, But there they are. <sup><a href="https://app.paircast.io/c/t78vtYge5/189440">03:09</a></sup>

`chrome.exe > Documentation | Electron - Google Chrome` <sup><a href="https://app.paircast.io/c/t78vtYge5/190166">03:10</a></sup>

And we're just going to copy and paste this file here. <sup><a href="https://app.paircast.io/c/t78vtYge5/196660">03:16</a></sup>

`chrome.exe > Notifications (Windows, Linux, macOS) | Electron - Google Chrome` <sup><a href="https://app.paircast.io/c/t78vtYge5/200168">03:20</a></sup>

Into the main Js. <sup><a href="https://app.paircast.io/c/t78vtYge5/202230">03:22</a></sup>

And this is going to enable us to use notifications Electron. So now when I run this code, we got a basic notification from electron. <sup><a href="https://app.paircast.io/c/t78vtYge5/205190">03:25</a></sup>

<sup><a href="https://app.paircast.io/c/t78vtYge5/207620">03:27</a></sup>

```diff
Commit 8b55da3f7207c1efa9975653d2f6ec8877d93b54
--- index.html
+++ index.html
@@ -0,0 +1,25 @@
+<!DOCTYPE html>
+<html>
+
+<head>
+    <meta charset="UTF-8">
+    <title>Hello World!</title>
+    <meta http-equiv="Content-Security-Policy" content="script-src 'self' 'unsafe-inline';" />
+    <style type="text/css">
+        body {
+            background-color: white;
+        }
+    </style>
+</head>
+
+<body>
+    <h1>Hello World!</h1>
+    We are using node
+    <script>document.write(process.versions.node)</script>,
+    Chrome
+    <script>document.write(process.versions.chrome)</script>,
+    and Electron
+    <script>document.write(process.versions.electron)</script>.
+</body>
+
+</html>

```

<sup><a href="https://app.paircast.io/c/t78vtYge5/207620">03:27</a></sup>

```diff
Commit 8b55da3f7207c1efa9975653d2f6ec8877d93b54
--- main.js
+++ main.js
@@ -1,5 +1,17 @@
 const { app, BrowserWindow } = require('electron')
 
+const { Notification } = require('electron')
+
+function showNotification() {
+    const notification = {
+        title: 'Basic Notification',
+        body: 'Notification from the Main process'
+    }
+    new Notification(notification).show()
+}
+
+app.whenReady().then(createWindow).then(showNotification)
+
 function createWindow() {
     const win = new BrowserWindow({
         width: 800,

```

`ConEmu64.exe > Cmder` <sup><a href="https://app.paircast.io/c/t78vtYge5/210170">03:30</a></sup>

Great. <sup><a href="https://app.paircast.io/c/t78vtYge5/215760">03:35</a></sup>

Already. So to recap here. <sup><a href="https://app.paircast.io/c/t78vtYge5/218480">03:38</a></sup>

`obs64.exe > OBS 25.0.8 (64-bit, windows) - Profile: Untitled - Scenes: Untitled` <sup><a href="https://app.paircast.io/c/t78vtYge5/220174">03:40</a></sup>

We've tracked all our changes, or about four minutes in <sup><a href="https://app.paircast.io/c/t78vtYge5/225180">03:45</a></sup>

Again. We have this branch or working out of this pair cast branch. And if you noticed here if we do a get log <sup><a href="https://app.paircast.io/c/t78vtYge5/228490">03:48</a></sup>

`ConEmu64.exe > Cmder` <sup><a href="https://app.paircast.io/c/t78vtYge5/230176">03:50</a></sup>

Bring us into interview. I'll keep it there. <sup><a href="https://app.paircast.io/c/t78vtYge5/235210">03:55</a></sup>

If we do get Logue, you'll notice that paradise is automatically made a bunch of commits for us so we can see <sup><a href="https://app.paircast.io/c/t78vtYge5/239220">03:59</a></sup>

<sup><a href="https://app.paircast.io/c/t78vtYge5/245690">04:05</a></sup>

<a href="https://app.paircast.io/c/t78vtYge5/245690"><img src="https://app.paircast.io/replay/f2ace53b-b035-4d95-9f04-2bec2eabd414/screenshot?timestamp=245690&shareKey=yw6BsOjDjCgcqNEDjlUTg" width="300" alt="Paircast Screenshot at Minute 4" /></a>

The history of all of our changes, So let's leave that <sup><a href="https://app.paircast.io/c/t78vtYge5/245690">04:05</a></sup>

And now we're going to finish and publish. <sup><a href="https://app.paircast.io/c/t78vtYge5/250330">04:10</a></sup>
