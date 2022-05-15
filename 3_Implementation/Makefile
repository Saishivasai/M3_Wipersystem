all:clean main.o wiper.elf run

main.o:main.c
	arm-none-eabi-gcc -c -mcpu=$(MACH) -mthumb -std=gnu11 -Wall -O0 -o $@ $^

wiper.elf:main.o driver.o startup.o
	arm-none-eabi-gcc -nostdlib -T stm32_ls.ld -o $@ $^

run:
	qemu-system-gnuarmeclipse.exe -M STM32F4-Discovery -mcu STM32F407VG -kernel wiper.elf
  
clean:
	-rm -rf *.o *.elf
