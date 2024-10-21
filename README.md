# Motivate Mechanicus

```
                                  0000                                     
                                  000000000000                             
                                  00000000000000000                        
                                  00000000000000000000                     
                              00000  0000000000000000000                   
                     000      00000  0000000000000000000000                
                  0000000     00000  00000000   000000000000               
                 000000000000000000       00      000000000000             
                  00000000000000000              00000000000000            
                  00000000000000  00000          0000000000000000          
           00    0000000000       000000000       0000000000000000         
         0000000000000000         00000000000       00    00000000         
        000000000000000           000000000000             00000000        
        00000000000000            00000000000000           000000000       
          00000000000             00000000000000        000000000000       
           0000000000             00000000000000        0000000000000      
           0000000000             00000000000000         000000000000      
        0000000000000             00000000000000         000000000000      
     00000000000000000            0000000000000               00000000     
     00000000000000000            0000000000000               00000000     
     000000000000000000           0000000000000               00000000     
      0000000000000000            0000000000000          000000000000      
           0000000000   0000000   00000     0000        0000000000000      
           0000000000   000000000 000       0000        0000000000000      
           00000000000   000     00000000000000         0000000000000      
        000000000000000         000 0000000000            0000000000       
        00000000000000000 00    0 00000000000              00000000        
         0000000000000000000      00000000          00    000000000        
           000  00000000000       00000000        0000000000000000         
                  000000000  0 00 00000000       0000000000000000          
                  00000000000000000              000000000000000           
                 000000000000000000      000      000000000000             
                  0000000     00000  00000000   0000000000000              
                     000      00000  0000000000000000000000                
                              00000  00000000000000000000                  
                                  00000000000000000000                     
                                  00000000000000000                        
                                  0000000000000                            
                                  00000
```

A sacred script to dispense the blessed words of the Adeptus Mechanicus. Highly influenced by the ancient Unix command [fortune](https://en.wikipedia.org/wiki/Fortune_(Unix)), yet now harnessing the holy data from the wisdom of the Omnissiah and the sacred Mechanicus texts.

## Features
* Output blessed by the Holy Color-Cogitators
* Supports `bash` and `zsh`, systems venerable enough for the Machine God

## Requirements

```
git
python 3.x
```

## Installation Rituals
The rites of installation vary depending on the system of worship. Ensure you have anointed the terminal with the appropriate holy oil or incense, lest the Omnissiah's wrath be incurred.

### Linux/MacOS - Rite of Installation

*Required Incense:* Myrrh of the Omnissiah and Sacred Chromium Oil

Proceed thusly:

```
$ git clone https://github.com/andra-putra/motivate-mechanicus.git
$ cd motivate-mechanicus/motivate
$ sudo ./install.sh
$ source ~/.bashrc
```

Zsh users should replace `.bashrc` with `.zshrc`.

### Alternate Rite (Without Root Privilege)
*Required Oil:* Blessed Lubricant of the Lesser Cog
If thou lackest root privilege, proceed thusly:

```
$ git clone https://github.com/andra-putra/motivate-mechanicus.git
$ cd motivate-mechanicus
$ ln -s $PWD/motivate/motivate.py moti
$ ln -s $PWD/dummy.sh mmoti

$ export PATH=$PWD:$PATH
$ # echo 'export PATH=$PWD:$PATH' >> ~/.bashrc
```

Invoke the sacred script with:
- `moti` (a single invocation) or
- `mmoti` (eternal invocation until manually interrupted)
Anoint the keyboard with Blessed Lubricant of the Lesser Cog before invoking the command line, and offer a prayer to the Machine Spirits residing within.

### Windows - Rite of Installation for Inferior Systems

*Required Oil and Incense:* Incense of the Abacus and Unction of Compatibility

To bring the Omnissiah's blessings to an inferior system:

* Ensure Python3 is on your system path, lest the Omnissiah's blessings be absent.
* Clone the repository: `git clone https://github.com/andra-putra/motivate-mechanicus.git`.
* Add the path to your local clone to your system's sacred path.
* Invoke the motivator with `py -3 motivate.py` from the command prompt.

During these rituals, burn Incense of the Abacus to pacify the Machine Spirits of Windows, and apply Unction of Compatibility to the mouse and keyboard to ensure harmony.

## Updating the Wisdom Database

Should the holy quotes require renewal, anoint the USB port with the Oil of Data Transfer and proceed with the following rite:

```
$ git clone https://github.com/andra-putra/motivate-mechanicus.git
$ cd motivate-mechanicus
$ ./UPDATE
# Recite the following: "Blessed is the flow of data, may the Machine God permit this sacred update."
```

## Invocation of the Sacred Words

```
$ motivate

"Purification is the prelude to annihilation."
                -- Hagiographies of Saint Regulavis
```

++MACHINE BLESSING TERMINATION++
"By the light of the Omnissiah, may these words inspire the faithful and bring ruin to the heretek."
