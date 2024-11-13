# PolarSSL.ldg

Library using the LDG system and the mbedTLS 1.3.22 library.
Brings SSL/TLS layer (deprecated SSLv3.0 TLSv1.0 TLSv1.1, old TLSv1.2) to clients applications using MiNTnet and STinG/STiK TCP layers.

Used by :  
- Troll, usenet and email client.  
- Meg, mailbox checker and spam eraser.  
- Litchi, ftp client.  

Targets: 68000, 68020-060, ColdFire

Other programs can use it, please read the how-to and functions calls in the st-guide documentation.

# installation for makefiles

- pre-requisite: different targets of libpolarssl.a, libldg.a in /opt/cross-mint/m68k-atari-mint/lib/

- in an empty folder,  
   ```mkdir ./build/68000```  
   ```mkdir ./build/68020```  
   ```mkdir ./build/ColdFire```  

- get [polarssl.ldg.r9.zip](https://ptonthat.fr/files/polarssl/sources/polarssl.ldg.r9.zip) and unpack the contents of /polarssl.ldg/ to  
   ```./README.md```  
   ```./Makefile```  
   ```./main.c```  
   ```./transport.h```  
   ```./polarssl.ldg.xcodeproj```  

- polarssl.ldg.xcodeproj is for Xcode 16.0, you may not need it if you use something else.
