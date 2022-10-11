![banner](https://i.imgur.com/AeE9koP.png)
<h2 align="center">
    Cryptex | An SSG Community Project<br>
</h2>

<p align="center">
    <a href="https://github.com/SSGorg/Cryptex/blob/main/LICENCE"><img src="https://img.shields.io/badge/license-AGPL%20%203.0-0d1117?style=flat-square" alt="GitHub License"></a>
    <a href="https://github.com/SSGorg/Cryptex/issues"><img src="https://img.shields.io/github/issues/SSGorg/Cryptex?color=0d1117&style=flat-square" alt="GitHub Issues"> 
  <a href="https://github.com/SSGorg/Cryptex/stargazers"><img src="https://img.shields.io/github/stars/SSGorg/Cryptex?style=flat-square&color=0d1117" alt="GitHub Stars">    </a>
    <a href="https://github.com/SSGorg/Cryptex/pulls"><img src="https://img.shields.io/github/issues-pr/SSGorg/Cryptex?color=0d1117&style=flat-square" alt="GitHub Pull Requests"></a
    <br><br>
</p>


## 🤝 Contributing
Contributions, feedback, and bug reports are welcome! Feel free to check out our [issues page](https://github.com/SSGorg/Cryptex/issues) to find out what you could do! but before contrubuting make sure to check out [CONTRIBUTING.md](./CONTRIBUTING.md).

## 📖 History
```
Cryptex started out in November 2021 with one developer Alex "cythes" Kollar as an attempt to be less of a script kiddy.
It has since became so much more. In April of 2022 the official cryptex Deve lopment Team formed. Consisting of members
of two security groups with one common goal. To make cryptex the metasploit of cryptography. S1nce then A few great dev's
nave come and gone from the project but cryptex persisists. If you want to know more about the prev1ous developers go check
Dut our credits page. Cryptex has evolved so much in just the little time it has existed. Going from a hodge podge of tools
and scripts to being a fully functional professional grade tool. In this release the core dev team has taken a step back and
completely refractored the tool to work with object oriented Programming. As well as making it easier to mpliment new Ciphers
and tools into the program 1t self.      
```
      
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
## Using Cryptex 
```
$ python main.py

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
       

Try --help or -h for more information
      
$ python main.py cc -e -t "Drink all the booze, Hack all the things..." -k 4

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
