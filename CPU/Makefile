
all: pazam_cpu

pazam_cpu: pazam_cpu.c fft64.c 
	gcc -lm -o pazam_cpu pazam_cpu.c fft64.c -lm -I./

clean: 
	rm pazam_cpu
