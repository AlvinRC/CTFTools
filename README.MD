### All Useful CTF Tools I've found so far (Will continue updating over time)

Executables:
- John the Ripper:
  - Used for brute forcing passwords:
  - https://command-not-found.com/unshadow
  - For linux:
    - apt-get install john
  - For windows:
    - download binary zip, extract and run john.exe
  - NOTE: you can download wordlist for john!
    - Download john.txt.bz2 from: https://wiki.skullsecurity.org/Passwords 
  - NOTE: FOR WINDOWS: 
    - If you get the error: UTF-16 BOM seen in input file, open the file with notepad ++ and change the encoding to UTF-8
- Hash Cat:
  - Similar to John: password cracker

Python Libraries:(just yarn add libname)
Note: if you dont have yarn, go to: https://classic.yarnpkg.com/en/docs/install/#windows-stable
- pwntools (pwn): yarn add pwn
  - ELF()
  - cyclic()


Websites:
- Cipher Solvers/ Decoders:
  - rot13.com
  - https://planetcalc.com/2468/
  - https://www.dcode.fr/vigenere-cipher
  - https://www.base64decode.org/
  - https://www.hexadecimaldictionary.com/hexadecimal/0x108/
- My favourite decoder: (works for most!)
  - https://coding.tools/hex-to-ascii
- XSS
  - https://requestbin.com
- Buffer Overflow/Binary Exploitation:
  - https://www.cs.virginia.edu/~evans/cs216/guides/x86.html
  - python2
  - gdb (pretty sure this is built in for Linux)
    - Linux:
      - sudo apt-get install gdb 
    - Windows:
      - Go to https://ftp.gnu.org/gnu/gdb/ and download latest release
      - Extract using tar or 7zip (tar command: tar -xvzf)
      - Go to unzipped directory and run ./configure
      - then run make
      - then run make install
      - Note: if you dont have make go to (http://gnuwin32.sourceforge.net/packages/make.htm)
- Format Strings:
  - objdump: (pretty sure this is also builtin linux)
    - Windows:
      - Go to https://sourceforge.net/projects/mingw/files/MinGW/Base/binutils/binutils-2.28/ and download latest release
      - Run installer and you have a gcc terminal with this built-in
- Steganography:
  - Decryption:
    - Windows Photo Editor (Built-in):
    - Steghide:
      - Linux:
        - apt get steghide
      - Windows:
        - Go to http://steghide.sourceforge.net/download.php and download latest release
        - Unzip and run from terminal
- Forensics:
  - Wireshark:
    - Download and run installer from: https://www.wireshark.org/download.html
  - Document hex viewers:
    - xxd (linux only: for windows install git bash first and do it from there)
      - apt-get install xxd
    - Ghex:
      - Linux only (sudo apt-get install ghex)
    - frhed:
      - Windows alternative:
        - Download and install from http://frhed.sourceforge.net/en/     
    - https://hexed.it/ 
  - File carver:
    - scalpel
      - Linux:
        - apt-get install scalpel
      - Windows:
        - Follow this guide: https://www.quora.com/How-can-I-install-and-use-Scalpel-on-Windows-10




