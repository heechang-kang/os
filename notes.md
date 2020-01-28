# notes

## writing OS

prerequisites\
sudo apt-get install
    g++ binutils libc6-dev-i386

when computer starts : 
    cpu : AX,EX, instructor pointer\
    take data from BIOS : copy firmware to RAM\
    instructor pointer to firmware in RAM\
    storage load into RAM from MBR(masterBootrecorder) : bootloader into RAM\
    look into /boot/grub/grub.cfg  <--os types\
    /boot/kernel.bin load into RAM\
    loader.s -> loader.o kernel.cpp-> kernel.o\
    ld(linker) : combine to kernel.bin, so bootloader can find them

esp register
stack pointer behind the space




