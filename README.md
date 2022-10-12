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
Cryptex started out in November 2021 with one developer Alex "cythes" Kollar as an attempt to be less of a script kiddy.
It has since became so much more. In April of 2022 the official cryptex Development Team formed. Consisting of members
of two security groups with one common goal. To make Cryptex the Metasploit of cryptography. Since then A few great dev's
nave come and gone from the project but Cryptex persists. If you want to know more about the previous developers go check
out our credits page. Cryptex has evolved so much in just the little time it has existed. Going from a Hodge-podge of tools
and scripts to being a fully functional professional grade tool.    

As of the Pumpkin Patch 00 release the core dev team has taken a step back and completely refactored the tool to work with object oriented Programming. As well as making it easier to implement new Ciphers
and tools into the program it self.  
      
## 🛠️Basic Help:
```
$ python main.py --help
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
```
$ python main.py cc
 
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
  <a href="https://discord.gg/899KQFeAXrF"><img src="https://discordapp.com/api/guilds/879757204620726362/widget.png?style=banner3" alt="Discord Server"></a>
  
## 🔧 Issues
If you face any problems while using the application, please open an issue here
 
## 🤝 Contributing
Contributions, feedback, and bug reports are welcome! Feel free to check out our [issues page](https://github.com/SSGorg/Cryptex/issues) to find out what you could do! but before contrubuting make sure to check out [CONTRIBUTING.md](./CONTRIBUTING.md).

## Using Cryptex 
**Bringing up the list of encryptions**  
![image](https://user-images.githubusercontent.com/89718570/195420448-c681d6c2-b569-4937-8dc3-ef7fa53ddec8.png)  

**Getting help with a cipher**  
![image](https://user-images.githubusercontent.com/89718570/195420584-08500d43-d6b5-4162-a468-f4aa91250336.png)  

**Encryption with ceasar cipher**  
![image](https://user-images.githubusercontent.com/89718570/195420722-e69f403f-5f2d-4656-9159-b500225bfd5a.png)

