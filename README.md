<div align="center">
  <img src="https://i.imgur.com/AeE9koP.png" alt="Logo">
  <h1> Cryptex | An SSG Community Project </h1>
  <h3>Locks only exist to keep honest people honest</h3>
</div>

<p align="center">
    <a href="https://github.com/SSGorg/Cryptex/blob/main/LICENCE"><img src="https://img.shields.io/badge/license-AGPL%20%203.0-0d1117?style=flat-square" alt="GitHub License"></a>
    <a href="https://github.com/SSGorg/Cryptex/issues"><img src="https://img.shields.io/github/issues/SSGorg/Cryptex?color=0d1117&style=flat-square" alt="GitHub Issues"> 
    <a href="https://github.com/SSGorg/Cryptex/stargazers"><img src="https://img.shields.io/github/stars/SSGorg/Cryptex?style=flat-square&color=0d1117" alt="GitHub Stars"></a>
    <a href="https://github.com/SSGorg/Cryptex/pulls"><img src="https://img.shields.io/github/issues-pr/SSGorg/Cryptex?color=0d1117&style=flat-square" alt="GitHub Pull Requests"></a>
</p>

## 📖 History
Cryptex started out in November 2021 with one developer **Alex "cythes" Kollar** as an attempt to be less of a script kiddy.
It has since became so much more. As of april 2022 Alex decided to open the project up to the SSG community to some absolutely incredible results. At this point the **SSG | Cryptex Dev Team** was founded with a the idea of building cryptex into a cryptography tool that people could use, install and add to with ease. Similar to *metasploit*. The project and team has evolved so much in just the little time it has existed.  
  
Cryptex itself maturing from Alex's seventeen original Hodge-podge of unoptimized tools, to what is now a professional grade cryptography toolkit. **Cryptex** is backed by a passionate team of devs ranging from beginners looking for a place to start to advanced devs who want a challenge. We even have a few idea men who come up with whacky encryption ideas for us to try to impliment. (Static Encryption. Go check it out.) Last but 110% not least our sponors who believe in the project enough to financially back us. 
  
## 🗓️ Upcoming Release
### Cryptex Beta V0.1.0 - Pumpkin Patch 00  
> After participation in Hacktoberfest 2022 we are going to put the collective updates from the event into a new realease. We are Dubbing the Pumpkin Patch. The plan is every year we do Hacktoberfest we will add a new Pumpkin Patch to Cryptex.  
  
Notes: 
- We are moving away from the *Earth Invader*. 
- complete rebuild of cryptex to work with *Object Oriented Programming*. 
- Its now easier to implement new Ciphers and tools.   
- Installer has been rewritten from the ground up in *python*.
- The main menu can now dynamically add ciphers and tools to the list.
- We brought back the OG *'Cryptex UI'* (We made it look pretty again)
- Implimented a system that lets us use Ascii art for version names.

All of this is pushing Cryptex ever closer to its goal of becoming the `metaploit of cryptography`  
      
## 🛠️Basic Help:
Command:
```
python main.py --help
```
Output:
```
usage: main.py [-h] [-e] [-d] [-t TEXT]
               [-k KEY] [-ex EXCLUDE]
               [-o OUTPUT] [-i INPUT]
               [-iw IMAGEWIDTH] [-m]
               [-lang] [-src SRC_LANG]
               [-dest DEST_LANG]
               [-len LENGTH]
               [cipher]

positional arguments:
  cipher              The cipher name

optional arguments:
  -h, --help          show this help
                      message and exit
  -e, --encode        Encode mode
  -d, --decode        Decode mode
  -t TEXT, --text TEXT
                      The input text
  -k KEY, --key KEY   The key
  -ex EXCLUDE, --exclude EXCLUDE
                      The exclude list
  -o OUTPUT, --output OUTPUT
                      output file
  -i INPUT, --input INPUT
                      input file
  -iw IMAGEWIDTH, --imageWidth IMAGEWIDTH
                      image width
  -m, --monocromatic  monocromatic
  -lang               show languages
  -src SRC_LANG       source language
  -dest DEST_LANG     destination language
  -len LENGTH         length
```
### If you want help with an individual cipher you can simply call the cipher like so:
Command:
```
python main.py cc
```
Output:
```
 
        ### Modes
        -d / --decode ---- decode
        -e / --encode ---- encode

        ### Input
        -t / --text ------ input text
        -k / --key ------- shift key
        -ex / --exclude -- exclude list

        ### Examples
        python main.py cc -e -t "hello" -k 10
        python main.py cc -d -t "hello" -k 10
        python main.py cc -e -t "hello" -k 10 -ex '123456789'
        python main.py cc -d -t "hello" -k 10 -ex '123456789'
       
Please select a mode
Try --help or -h for more information
```
## 🖐️ Get in touch
### You can join in on chatting with the dev team on our discord server
  <a href="https://discord.gg/899KQFeAXr"><img src="https://discordapp.com/api/guilds/879757204620726362/widget.png?style=banner3" alt="Discord Server"></a>
  
## 🔧 Issues
If you face any problems while using the application, please open an issue [here](https://github.com/SSGorg/Cryptex/issues).
 
## 🤝 Contributing
Contributions, feedback, and bug reports are welcome! Feel free to check out our [issues page](https://github.com/SSGorg/Cryptex/issues) to find out what you could do! but before contrubuting make sure to check out [CONTRIBUTING.md](./CONTRIBUTING.md).

## Using Cryptex 
Command:
```
python main.py
```
Output:
```

               _____              __         
              / ___/_____ _____  / /______ __
             / /__/ __/ // / _ \/ __/ -_) \ /
             \___/_/  \_, / .__/\__/\__/_\_\ 
              V:0.0.1/___/_/  OOP Edition
              Locks only exist to keep honest 
                       people honest
          
|-- ciphers---------------------------|-- short name ------|
|      Plain text cipher              |      text          |
|      Caesar Cipher                  |      cc            |
|      Rot 13                         |      r13           |
|      Reverse cipher                 |      rc            |
|      Rot 47                         |      r47           |
|      Base 64                        |      b64           |
|      Morse code                     |      mor           |
|      XOR (Exclusive Or) Cipher      |      xor           |    
|      Vignere Cipher                 |      vig           |
|      Static Encryption              |      se            |
|      Octal                          |      oct           |
|      L33t Sp34k                     |      l33t          |
|      Multiplicative Cipher          |      mc            |
|      Menc                           |      menc          |
|      MonoAlphabetic cipher          |      ma            |
|-- tools-----------------------------|-- short name ------|
|      QR Code Generator              |      qr            |
|      Google Translate               |      translate     |
|      Password generator             |      pswd          |
|-- datatypes-------------------------|-- short name ------|
|      Hex Encoder / Decoder          |      hex           |
|      Binary Translator              |      bin           |
|-- hash functions--------------------|-- short name ------|
|      MD5                            |      md5           |
|-------------------------------------|--------------------|

Try --help or -h for more information
```
Command:
```
python main.py cc
```
Output:
```
 
        ### Modes
        -d / --decode ---- decode
        -e / --encode ---- encode

        ### Input
        -t / --text ------ input text
        -k / --key ------- shift key
        -ex / --exclude -- exclude list

        ### Examples
        python main.py cc -e -t "hello" -k 10
        python main.py cc -d -t "hello" -k 10
        python main.py cc -e -t "hello" -k 10 -ex '123456789'
        python main.py cc -d -t "hello" -k 10 -ex '123456789'
       

Try --help or -h for more information
```
Command:
```
python main.py cc -e -t "Drink all the booze, Hack all the things..." -k 4
```
Output:
```
               _____              __         
              / ___/_____ _____  / /______ __
             / /__/ __/ // / _ \/ __/ -_) \ /
             \___/_/  \_, / .__/\__/\__/_\_\ 
              V:0.0.1/___/_/  OOP Edition
              Locks only exist to keep honest 
                       people honest
          

        ------ Cipher: cc -- Mode: Encode ------
        Input      | Drink all the booze, Hack all the things...
        Output     | Hvmro epp xli fssdi, Lego epp xli xlmrkw...

```
