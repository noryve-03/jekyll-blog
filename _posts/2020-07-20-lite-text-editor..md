---
title: "Discover the awesome lite text editor 😃 💻 "
author: Freeman Irabaruta
date: 2020-07-20 11:33:00 +0800
categories: [Blogging,Coding]
tags: [C_lang,lua]
math: true
mermaid: true
image:
  src: https://raw.githubusercontent.com/snow-blade/blog/master/content/assets/lite.png
---

### What the heck is it  🕶

The lite text editor is an open-source, modern, beautiful and extremely customizable text editor,<br/> it also is very lightweight(2 mb).<br/> The core is written written in c using the [SDL2]() library and it does low level things like drawing the window, drawing text, drawing shapes,setting the font, and handles the 'fronted' as I may say that is written in the [lua](https://www.lua.org/) programming language,<br/> it's also growing very fast as in only 4 months it managed to have more than 3.4k GitHub stars.
<br/>
Here is a little screenshot of it:

![lite](https://raw.githubusercontent.com/snow-blade/blog/master/content/assets/lite.png)

### How to install 💻

##### You can either download the precompiled binaries By:

  Going to: [https://github.com/rxi/lite/releases/](https://github.com/rxi/lite/releases/) then select lite.zip, it should give you access to a zip file, then unzip it.<br/>
  If you're on a windows platform, just open the file named lite.exe but if you're on linux/macOs open the file named lite, and everything should work just fine.

##### Or you can compile from source: 

- Linux:

  On debian based distros run :

  ```bash
  sudo apt install libSDL2-dev
  ```

  On rheel distros:

  ```bash
  sudo dnf install libSDL2-devel
  ```

  On arch-based distros:

  ```bash
  sudo pacman -S sdl2
  ```

  Then clone the repo:

  

  ```bash
  git clone https://github.com/rxi/lite.git
  ```

- OSX:

  Follow this tutorial: https://medium.com/@edkins.sarah/set-up-sdl2-on-your-mac-without-xcode-6b0c33b723f7

After installing the required packages on both platforms, build lite with:

  ```bash
  cd lite&&./build.sh
  ```

   <p class='tip'>  <div class="tip-header">📓 📝 😎 tip</div> <br />  <br />Read the below link if you're on linux, for a better user experience</p> 
 <a href="https://github.com/rxi/lite/issues/134"> ➜➜ here ⬅⬅ </a>

### When would I need it 📑📑

Lite is not complete enough to be called an IDE but you can use it as an alternative to notepad/notepad++ and use it to open simple files like .txt or .c, .h or programs you want to quickly compile in a terminal.

<p class='tip'> <div class="tip-header">📓 📝 😎 tip</div> <br />  <br /> Lite has a console plugin to quickly compile or test your programs </p>
Download it here: <a href="https://github.com/a327ex/lite-plugins/blob/master/plugins/console.lua">https://github.com/a327ex/lite-plugins/blob/master/plugins/console.lua</a> and put it in the plugins folder.<br/>
As lite is extremely lightweight, it only requires =~2mb of storage and takes an insignificant amount of cpu, it's perfect for simple and fast file editing, it's also highly customizable, so you can use it to brush up those Lua and c skills

### Final words

I decided since long to use lite as my default text editor and use an IDE only when I need it as most of the programs I write, I eventually need to compile them using a terminal

<p class='tip'>  <div class="tip-header">📓 📝 😎 tip</div> <br />  <br />Please follow me on github<p>
That's it folks ☑️☑️, try it out and trust me you'll like this editor for it's simplicity and be amazed by it's functionalities that only fit  in 2mb of storage.









