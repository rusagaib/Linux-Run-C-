# Linux-Run-C-
Tutorial jalankan script c++ di linux, mulai dari install compiler setting library dsb..

# First Things First:
Instal compiler c++ di linux kita (ubuntu 16.04);

      sudo apt-get install build-essential
  
# Cek copiler anda versi berapa:

      gcc --version
  
# Setting library c++:
1. Copy file conio.h dari directory awal ke '/usr/include/'
   Run as root user:
   
       sudo su
      
       cd 'directory-awal'
      
       cp conio.h /usr/include/
      
# Cara Jalankan Script '.cpp' anda:
1. Compile dulu script dengan:

       g++ -o namafile namafile.cpp
      
2. Kemudian Jalankan script anda :

       ./namafile

# List Fungsi di (conio.h):
    cprintf
    cscanf
    gotoxy          
    clrscr          
    textcolor       
    textbackground  
    wherex         
    wherey        
    getch          
    getche   
    ungetch
    kbhit          
    putch           
    putchar        
    cputs         
    clreol         
    insline (not implemented)       
    delline (not implemented)       
    cgets   (not implemented)       
    getpass (not implemented)        
    gettext (not implemented)
    _cprintf        
    _cscanf         
    _cputs          
    _getche         
    _kbhit          
    _putch          
    _ungetch
    
# Thanks To:
* conio4linux (Conio.h for linux)
* Copyright (C) 2013 by Carlos J. Pinto B.
* conio.h -- * @date 2013-11-05 * @version 0.3
