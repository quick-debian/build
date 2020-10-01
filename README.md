# Quick-Debian Build system.

  

### Features of the Quick Debian Build system:

 - Usage of Kconfig
 - Simple structure
 - Easy to adapt new Boards 
 - Flexible usage allowing for custom scripts
 - Creation of boot ready images

#### Usage
 Clone the Repositry
 ` git clone https://github.com/quick-debian/build.git `

Change into the repos root folder then run: 
 `make board_defconfig `
 
Replace `board_defconfig` with the defconfig of your Board.
  
If you want to make changes run: 
` make menconfig`

To create the Boot Image:
`make`

####  Structure of the Project
````
output  -> Output directory for Boot-Image,Bootloader,Kernel,Host-tools 
config  -> Directory used to store Board defconfigs
board   -> Contains Subdirectories for Board specific configurations
docs    -> Documentation files 
````


