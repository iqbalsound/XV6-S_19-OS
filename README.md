# XV6-S_19-OS
# Pre-Req for Running XV6
	git Installed
	GCC Installed
	qemu Installed
	aqemu Installed (Not Requried in most cases)
	gcc multilib Installed
	make installed
#Steps for Running XV6 on UBUNTU
#in terminal tyoe following commands
1 - git clone https://github.com/iqbalsound/XV6-S_19-OS.git XV6-S_19-OS
2 - cd XV6-S_19-OS
3 - make
4 - make qemu

# Output in terminal will be like following and identical output will appear in QEMU window
qemu-system-i386 -drive file=obj/kern/kernel.img,index=0,media=disk,format=raw -serial mon:stdio -gdb tcp::26000 -D qemu.log 
6828 decimal is XXX octal!
entering test_backtrace 5
entering test_backtrace 4
entering test_backtrace 3
entering test_backtrace 2
entering test_backtrace 1
entering test_backtrace 0
leaving test_backtrace 0
leaving test_backtrace 1
leaving test_backtrace 2
leaving test_backtrace 3
leaving test_backtrace 4
leaving test_backtrace 5
Welcome to the JOS kernel monitor!
Type 'help' for a list of commands.
K> 

